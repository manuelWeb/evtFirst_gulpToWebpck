77c77
<   // .pipe(changed(src+'*.js'))
---
>   .pipe(changed(src+'*.js'))
131,133c131,133
<   gulp.watch([src+'*.{png,jpg,gif}'],['script','images','sass','slim'])
<   gulp.watch(['source.json', src+'*.slim'],['script','slim','images']);
<   gulp.watch(src+'*.scss',['script','sass','slim','images']);
---
>   gulp.watch([src+'*.{png,jpg,gif}'],['images','sass','slim'])
>   gulp.watch(['source.json', src+'*.slim'],['slim','images','script']);
>   gulp.watch(src+'*.scss',['sass','slim','images','script']);
