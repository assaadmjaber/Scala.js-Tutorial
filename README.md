# Scala.js-Tutorial

This project creates a web application entirely using Scala.js. The code inside TutorialApp.scala is optimized by running `fastLinkJS` during development and then `fullLinkJS` during production which optimizes the JavaScript code. The tutorial creates a button and a Hello world message. Upon clicking the button, the message 'You clicked the button!' appears. 

The resulting code from the optimization can be tested in a web browser by going to `scalajs-tutorial.html` and right-click-opening it in a web browser. 

To both run and test the application using the full-optimized version from sbt change the stage using `set scalaJSStage in Global := FullOptStage`.

<img width="1624" alt="Screenshot 2023-12-06 at 16 43 32" src="https://github.com/assaadmjaber/Scala.js-Tutorial/assets/149254059/50591d84-e0ab-40df-8fe9-1424351040a0">

Link to tutorial: https://www.scala-js.org/doc/tutorial/basic/index.html
