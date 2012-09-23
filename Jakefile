desc('This is the default task.');
task('default', ['build']);

desc('Build via docco');
task('build', function () {
    var command = './node_modules/.bin/docco -o . index.js -t index.jst';
    console.log('Building index.html via docco')
    jake.exec(command);
});
