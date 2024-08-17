https://gettaurus.org/docs/JMeter/

Run JMX directly:
bzt main.jmx -report


Run JMX with execution YML:
bzt taurus-execution.yml -o settings.artifacts-dir=.\artifacts -o modules.jmeter.properties.withCI=true


bzt taurus-execution.yml -o settings.artifacts-dir=.\artifacts -o modules.jmeter.properties.withCI=true