module.exports = function(grunt) {
    grunt.initConfig({
        imagemin: {
            release: {
                files: [{
                    expand: true,
                    src: ['src/images/*.png']
                }],
                options: {
                    optimizationLevel: 3
                }
            }
        },

        uglify: {
            my_target: {
                files: {
                    'src/js/index.min.js': ['src/js/jquery-3.2.1.js']
                }
            }
        }
    });

    grunt.loadNpmTasks('grunt-contrib-imagemin');
    grunt.loadNpmTasks('grunt-contrib-uglify');
};