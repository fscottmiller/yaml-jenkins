// needs pipeline utility steps plugin
node {
    def config = readYaml file: '.devops.yaml'

config['jobs'].each {
    echo "${it}"
}
}
