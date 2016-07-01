# How to Use

Only to be used for the lols.

- (optional) Watch the Mr. Trololo video: https://www.youtube.com/watch?v=oavMtUWDBTM
- Clone this repo
- Make sure node is installed
- From your CLI, `cd` into the project directory and run the following:

```
$ node
> var fs = require('fs');
> var uglify = require('./uglify-js');
> fs.readFile('./uglify-js.js', 'utf8', function(err,data){console.log(uglify(data));});
```

- If on OSX, copy the result, `control+c` two times, and then run:

```
$ say "function uglify(trol,trolol){trolol||(trolol={});var trololol=uglify.parser,trolololol=uglify.uglify,trololololol=trololol.parse(trol,trolol.strict_semicolons);trololololol=trolololol.ast_mangle(trololololol,trolol.mangle_options),trololololol=trolololol.ast_squeeze(trololololol,trolol.squeeze_options);var trolololololol=trolololol.gen_code(trololololol,trolol.gen_options);return trolololololol}uglify.parser=require("./lib/parse-js"),uglify.uglify=require("./lib/process"),uglify.consolidator=require("./lib/consolidator"),module.exports=uglify"
```
