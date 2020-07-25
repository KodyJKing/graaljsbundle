# graaljsbundle
This is a repackaging of graal.js libraries to avoid dependency conflicts. I use this in my mod Silicon Golems.
It hides the objectweb.asm and ibm.icu packages, but leaves the graal packages exposed.

## Building
Run

    gradlew shadowJar

The output will be under build/libs
