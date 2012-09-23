desc('This is the default task.');
task('default', ['build']);

desc('Build via docco');
task('build', function () {
    var command = './node_modules/.bin/docco -o . index.js -t index.jst';
    console.log(command);
    jake.exec(command);
});
