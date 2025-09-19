pipeline {
agent none
stages {
stage("Build") {
agent any
steps {
echo "This is just to print in build stage"
}
}
stage("Test") {
agent any
steps {
echo "This is to test later from build stage"
}
}
}
}
