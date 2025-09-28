\# AudioPFile



\*\*AudioPFile\*\* is a tool for systematic management of a personal music collection.  

The name is a wordplay: \*audiophile\* (music enthusiast) + \*file\* (filesystem structure).



\## Project Goals

\- 📂 Deterministic directory structure generated from metadata  

\- 📝 Normalization and consolidation of tags (no duplicates like "Beyonce" vs "Beyoncé")  

\- 🔄 Autocomplete powered by your own catalog database  

\- ✅ Audit of the existing filesystem and assisted correction  

\- 🔊 Audio data integrity checks  

\- 🎧 Lossless → lossy conversion for mobile devices  



\## Module Roadmap

1\. \*\*Scanner (CLI)\*\* – read metadata and export to JSON  

2\. \*\*Normalizer (CLI)\*\* – unify text and aliases  

3\. \*\*PathResolver (CLI)\*\* – generate target paths  

4\. \*\*Writer (CLI)\*\* – safe moves/copies  

5\. \*\*Catalog DB\*\* – SQLite with autocomplete  

6\. \*\*Auditor\*\* – check existing structure  

7\. \*\*Integrity\*\* – validation and checksums  

8\. \*\*Transcoder\*\* – conversion to profiles  

9\. \*\*GUI (Qt)\*\* – visual interface over all modules  



\## Project Status

🚧 In development – first module: \*\*Scanner\*\*.



