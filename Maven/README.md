## Show outdated dependency versions Maven projects
`mvn versions:display-dependency-updates`

## Unused dependencies
`mvn dependency:analyze`

## Generate CVE report
`mvn org.owasp:dependency-check-maven:1.4.0:aggregate`

## Maven custom settings
`mvn --settings ~/configs/settings.xml`

## Creating uber jar
`mvn assembly:single -DdescriptorId=jar-with-dependencies`

## Skip tests during installing
`mvn clean install -DskipTests`

## Proxy
`set MAVEN_OPTS=-Dhttp.proxyHost=myproxy -Dhttp.proxyPort=3128 -Dhttps.proxyHost=myproxy -Dhttps.proxyPort=3128`

