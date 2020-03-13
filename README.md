# PESAN ERROR NYA 

Output conflict: multiple input files are writing to `_site/nim/index.html`. Use distinct `permalink` values to resolve this conflict.
  1. ./nim/index.njk
  2. ./nim/nim.njk

`DuplicatePermalinkOutputError` was thrown:
    (Repeated output has been truncated…)
        at TemplateMap.checkForDuplicatePermalinks (/usr/local/lib/node_modules/@11ty/eleventy/src/TemplateMap.js:533:13)
        at TemplateMap.cache (/usr/local/lib/node_modules/@11ty/eleventy/src/TemplateMap.js:306:10)
        at processTicksAndRejections (internal/process/task_queues.js:97:5)
        at async TemplateWriter._createTemplateMap (/usr/local/lib/node_modules/@11ty/eleventy/src/TemplateWriter.js:133:5)
        at async TemplateWriter.write (/usr/local/lib/node_modules/@11ty/eleventy/src/TemplateWriter.js:168:5)
        at async Eleventy.write (/usr/local/lib/node_modules/@11ty/eleventy/src/Eleventy.js:659:13)
        at async Eleventy.watch (/usr/local/lib/node_modules/@11ty/eleventy/src/Eleventy.js:573:5)
