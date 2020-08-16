#!/usr/bin/env groovy
pipeline {
agent any
stages {
stage('Clone') {
steps {
withCredentials(){
bat("""
git clone https://github.com/imimimi3/time_bot /var/gitbot

echo "pulled the code"
""")
echo 'Clone...'
}
}
}
}
}
