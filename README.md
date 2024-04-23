# Kotlin Word Count Tool

This repository hosts a custom implementation of the Unix `wc` (word count) tool, developed in Kotlin. The project serves as a learning platform for enhancing Kotlin proficiency through practical coding challenges inspired by [John Crickett's Coding Challenges FYI](https://codingchallenges.fyi/challenges/challenge-wc/).

## Project Overview

The goal of this project is to recreate the functionality of the traditional Unix `wc` command, which provides information about the number of lines, words, and characters in a text file. This implementation focuses on mastering Kotlin features and best practices through incremental development and feature enhancement.

## Features

The current version of this Kotlin `wc` tool supports:
- Character counting: `ccwc -c filename.txt`

Future implementations will aim to include:
- Word counting
- Line counting
- Additional command-line options for flexible file analysis

## Getting Started

### Prerequisites

Ensure you have the following installed:
- JDK 11 or higher
- Gradle 7.0 or higher (if you want to build from sources)

### Building the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/kotlin-wc-tool.git
   cd kotlin-wc-tool
   ```
2. Build with Gradle
   ```bash
   ./gradlew build
   ```
3. Run the tool
   ```bash
   ./gradlew run --args="-c test.txt"
   ```
   
Alternatively, you can build a fat JAR and run it directly:

   ```bash
   ./gradlew jar
   java -jar build/libs/kotlin-wc-tool.jar -c test.txt
   ```

## Acknowledgments
- Thanks to [John Crickett and Coding Challenges FYI](https://codingchallenges.fyi) for the inspiration and challenge guidelines that sparked this project. 
- Special thanks to the Kotlin community for providing extensive resources and support.