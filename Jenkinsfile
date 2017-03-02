node('master'){
    def test= BUILD_ID
git 'https://github.com/kuldeepdarmwal/ecomm.git'
sh 'echo ${BUILD_ID}'
    

sh 'echo \${BUILD_ID}  asdfasd'

echo "id is ${test}"     

//sh 'echo asdfasdfdsf \${test}  value lllll'
//command to replace Build_number at run time with current build number
sh 'sed -ie \'s/${BUILD_NUMBER}/\'"${BUILD_ID}"\'/g\' scriptfile.sh'
echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
//sh 'echo ${env.BUILD_ID} sdasdf asdf asdf'
//sh 'sed -ie \'s/${BUILD_NUMBER}/${test}/g\' scriptfile.sh'
}
