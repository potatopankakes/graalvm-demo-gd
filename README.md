# graalvm-demo-gd
Demostration of GraalVM for GoDaddy's Java Guild

## 1.0 Introduction
GraalVM's features have quite a bit of implication and opportunities which one can delve.
That said, this demo will only explore these areas:

- Download/Installation Primer
- Performance ByteCode Translation
- Guest Language Embedded in Java (JavaScript called from Java)
- Java called from Guest Language (JavaScript/NodeJS application calling Java)

## 2.0 Download/Installation
- https://github.com/graalvm/graalvm-ce-builds/releases (very recently moved from https://github.com/oracle/graal/releases)
- `asdf` (`asdf-vm` / asdf Version Manager)
 - https://asdf-vm.com/#/ ... plays nice with the overlapping tools
 - https://github.com/vic/asdf-graalvm ... if have issues, response on PRs is quick
- `gu` another option... did not explore
  -  https://www.graalvm.org/docs/reference-manual/install-components/

## 3.0 Running Java Faster... GraalVM's improved bytecode translation
Demo:
- https://github.com/potatopankakes/graalvm-java-performance-example

Comments:
- Indeed... GraalVM is much faster for straight computation

## 4.0 JavaScript Embedded in Java ... Host and Guest languages
Demo:
- https://github.com/potatopankakes/graalvm-java-javascript-example

Comments:
- Contexts
- Lots of possiblity for problems requiring plugin-type integration
- Not specific to JavaScript... any Guest language

## 5.0 Java Embedded in Javascript: JMX
Demo:
- https://github.com/potatopankakes/graalvm-javascript-jmx-example

Comments:
- Available with Bytecode ... not native
- https://www.graalvm.org/docs/reference-manual/languages/js/
- Context?

## 6.0 Additional Resources
- https://www.graalvm.org/
- https://github.com/graalvm/
- Focused Help:
  - Slack: https://www.graalvm.org/slack-invitation/
  - https://gitter.im/graalvm/home (old support area)
