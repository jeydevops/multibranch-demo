@Library('github.com/cloudbeers/multibranch-demo-lib') _
standardBuild {
    environment = 'golang:1.5.0'
    mainScript = '''
go build -v hello-world.go
'''
    postScript = '''
ls -l
./hello-world
'''
}
