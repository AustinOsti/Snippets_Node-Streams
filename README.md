# Snippets_Node-Streams

Sample demo of how node streams handle large data

1. Generate a large text file via running "node createlargefile.js"
2. Read the large file using fs.readFile, via "node readlargefile.js" 
3. Alternativley, read the large file using fs.createReadStream via node readlargefile-ns.js"

Note the difference!