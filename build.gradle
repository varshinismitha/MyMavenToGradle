plugins {
    id 'java'
    id 'application'   // ✅ REQUIRED for run
}

group = 'com.example'
version = '1.0-SNAPSHOT'

description = "MyMavenApp"

java {
    sourceCompatibility = JavaVersion.VERSION_1_8
    targetCompatibility = JavaVersion.VERSION_1_8
}

repositories {
    mavenCentral()
}

dependencies {
    testImplementation 'junit:junit:4.13.2'
}

application {
    mainClass = 'com.example.App'   // ⚠️ change if needed
}
