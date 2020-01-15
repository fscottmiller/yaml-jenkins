// needs pipeline utility steps plugin
node {
    git 'https://github.com/fscottmiller/yaml-jenkins'
    
    def config = readYaml file: '.devops.yaml'

    config['jobs'].each {
        echo "${it}"
    }
}
