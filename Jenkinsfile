#!/usr/bin/env groovy
properties([
   [$class: 'GithubProjectProperty',
   displayName: '',
   projectUrlStr: 'https://github.com/Ashokorg/Demo12/'],
   pipelineTriggers([githubPush()])])

node {
stage 'build'
echo 'hello world'
stage 'test'
echo 'hello veridic'
stage 'Deploy'
echo 'hello Georgia'
}
