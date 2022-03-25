<h1 align="center">
	<img
	width="150"
	src="/images/max-terminal.gif"></br>
	Circuit Breaker Policy - Maven archetype<br>     
</h1>

<h4 align="center">
	<a href="#overview">Overview</a> |
	<a href="#installation-instructions">Install Me</a> |
	<a href="#contributing">Contribute</a>
</h4>
	
<h3 align="center">
	This Mule project was created using the Maven archetype for Custom Policies. For more information, follow the Circuit Breaker custom policy tutorial.<br><br>
</h3>

## Tutorial and Video

For a step by step tutorial navigate to the MuleSoft developer website [here](https://developer.mulesoft.com/tutorials-and-howtos/custom-api-policies-api-manager-circuit-breaker-policy/)

## Overview

This Mule project was generated using the custom policy Maven archetype provided by MuleSoft (note that you need to replace `${orgId}` and `${policyName}` with your own values).

You need to do additional changes to your `settings.xml` Maven file before running this command. Please follow the tutorial for complete instructions.

```shell
mvn -Parchetype-repository archetype:generate \
-DarchetypeGroupId=org.mule.tools \
-DarchetypeArtifactId=api-gateway-custom-policy-archetype \
-DarchetypeVersion=1.2.0 \
-DgroupId=${orgId} \
-DartifactId=${policyName} \
-Dversion=1.0.0-SNAPSHOT \
-Dpackage=mule-policy
```

The project's directory has the following file structure:
```
<policyName>/
├── <policyName>.yaml
├── mule-artifact.json
├── pom.xml
└── src
   └── main
       └── mule
           └── template.xml
```

## Installation Instructions

For the full instructions, please follow the developer tutorial. This project is intended to be used to compare your results with ours.

## Contributing

Contributions are what make the MuleSoft community such an amazing place. Any contributions you make are **greatly appreciated**.
	
See [contributing.md](/contributing.md) for the MuleSoft Developer principles.
