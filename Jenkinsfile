pipeline {
agent {
label {
label "built-in"
customWorkspace "/mnt/data-1"
}
}
stages {
stage ("stage-1") {
steps {
sh "yum install tree -y"
}
}
}
}

