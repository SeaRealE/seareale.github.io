---
layout: default
title: archives
customjs:
 - 
---


<div>
    $files
</div>


<script>
    var fs = require('fs');
    var testFolder = './_posts';

    //var files = fs.readdirSync('./_posts/');

    fs.readdir(testFolder, function(error, filelist){
        console.log(filelist);
    })
</script>