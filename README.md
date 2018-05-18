# build-order
A showcase of wrong build order by maven when parallel option `-T 1C` enabled

sub/keystore is  stub that need to be replaced with a real keystore.

sub/pom.xml jarsigner properties need to be filled accordingly

The problem:

    mvn clean install -U -T 1C

makes that m3 is built before sub
