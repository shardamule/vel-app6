pipeline {
agent {
label {
label "slave-1"
customWorkspace "/mnt/data-1"
}
}
stages {
stage ("slave-1") {
steps {
sh "yum install tree -y"
}
}
}
}

