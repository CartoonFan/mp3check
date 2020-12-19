project('mp3check', 'cpp', version: '0.8.7', license: 'GPL-2.0',
        default_options: ['optimization=g',
                          'warning_level=3',
                          'cpp_std=c++20',
                          'b_coverage=true'])


inc = include_directories('include')


run_target('sonarqube_report',
           command: 'scripts/sonarqube_report.sh')


subdir('src')
