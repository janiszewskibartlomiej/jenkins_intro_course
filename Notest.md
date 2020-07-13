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

pierwszy job > new item > Enter an item name > freestail project > ok
jest pierwszy job - na stronei glownej mozemy kliknac config z nazwy joba z trujkat aroziwjanego > build > execute windows ... > wpisujemy komede konsolowa i save

Sciągnąć maven zip, rozpakowac w c://maven ustawić zmienne środkowiskowe M2_HOME c://apatche...  oraz MAVEN_HOME

go to projekt sklonowany i `mvn clean install`

download tomcat - server dla java > localhost:8888

jenkins new freestyle > add description [good practic]


Source Code Management > git > https://github.com/janiszewskibartlomiej/gol > save 

Build now - mamy sklonowane repo

configure > triggers > poll SCM > dodac polcenie crona https://pl.wikipedia.org/wiki/Cron > save

build > add builds step > maven > clean install > save
