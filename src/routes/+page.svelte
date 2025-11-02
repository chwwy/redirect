<script>
  const verseRef = "Hebrews 4:1";
  const targetUrl = "https://naorthern.medium.com/";
</script>

<!-- Google Font -->
<svelte:head>
  <link href="https://fonts.googleapis.com/css2?family=IM+Fell+DW+Pica&display=swap" rel="stylesheet">
  <style>
    .fell-font {
      font-family: 'IM Fell DW Pica', serif;
    }
  </style>
</svelte:head>

<div class="min-h-screen flex items-center justify-center bg-white dark:bg-neutral-900 p-6">
  <div class="max-w-2xl w-full shadow-xl border border-neutral-200 dark:border-neutral-700 overflow-hidden">
    
    <!-- Image header -->
    <div class="w-full">
      <img src="/sign-light.png" alt="Sign Light" class="block w-full dark:hidden" />
      <img src="/sign-dark.png" alt="Sign Dark" class="hidden w-full dark:block" />
    </div>

    <!-- Verse box -->
    <div class="fell-font text-center bg-neutral-50 dark:bg-neutral-800 p-8">
      <h1 class="text-neutral-600 dark:text-neutral-400 text-lg mb-2">{verseRef}</h1>
      <blockquote class="text-xl text-neutral-900 dark:text-neutral-100 mb-6">
        “Therefore, since the promise of <span class="font-semibold">entering his rest</span> still stands,
        let us be careful that none of you be found to have fallen short of it.”
      </blockquote>

      <p class="text-neutral-500 dark:text-neutral-400 text-lg">
        <a href={targetUrl} rel="noopener noreferrer"
          class="underline underline-offset-4 decoration-dashed hover:text-neutral-700 dark:hover:text-neutral-200">
          >>
        </a>
      </p>
    </div>
  </div>
</div>
