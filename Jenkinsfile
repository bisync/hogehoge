#!groovy

node('mac_server') {
	stage 'ホスト名の表示'
	sh 'echo `hostname`'
	stage 'mac_server-pwd表示'
	sh 'pwd'
	stage 'ビルドシェル実行'
	sh 'sh /Users/bisync/jenkins/workspace/jobname/test.sh'
}
