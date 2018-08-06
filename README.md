The Jenkins 'warnings' plug-in collects compiler warnings of the project modules and visualizes the results. 
It has built-in support for numerous static analysis tools (including several compilers), see the 
[warning package](src/main/java/io/jenkins/plugins/analysis/warnings) 
for a complete list of supported formats. If your tool is not yet supported you can either define a new parser in the
user interface or provide a parser within a new small plug-in. If the parser is useful for other teams please share it 
and provide pull requests for the [warnings plug-in](https://github.com/jenkinsci/warnings-plugin/pulls) and 
the [analysis parsers library](https://github.com/jenkinsci/analysis-model/).

For more details please refer to the corresponding [Jenkins wiki page](https://wiki.jenkins.io/x/G4CGAQ).

All source code is licensed under the MIT license.

[![Jenkins](https://ci.jenkins.io/job/Plugins/job/warnings-plugin/job/3.0/badge/icon)](https://ci.jenkins.io/job/Plugins/job/warnings-plugin/job/3.0/)
[![Travis](https://img.shields.io/travis/jenkinsci/warnings-plugin.svg)](https://travis-ci.org/jenkinsci/warnings-plugin)
[![Codecov](https://img.shields.io/codecov/c/github/jenkinsci/warnings-plugin/5.0.svg)](https://codecov.io/gh/jenkinsci/warnings-plugin/branch/5.0)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/jenkinsci/warnings-plugin.svg)](https://github.com/jenkinsci/warnings-plugin/pulls)
![JDK8](https://img.shields.io/badge/jdk-8-yellow.svg)
[![License: MIT](https://img.shields.io/badge/license-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
