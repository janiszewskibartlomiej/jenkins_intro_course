pobranie http://mirrors.jenkins-ci.org/war/latest/jenkins.war
to jest pakiet dla java

instalacja jenkins.war po pobraniu [potrzebna java max 11]:

`java -jar jenkins.war`

trzeba skopiowac passwort > go tu localhost:8080  wkleic password i sie zarejestrowac

komendy http://localhost:8080/cli/

The full list of commands is available at http://your-jenkins/cli

The command for a clean shutdown is http://your-jenkins/safe-shutdown

You may also want to use http://your-jenkins/safe-restart

w celu automatycznego odpalania trzeba uruchomic z cmd z uprawnieniami admina i odpalic jenkins, a nastepnie menage setings i inslat on windows
