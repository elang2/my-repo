**JMeter Plugin for CoAP protocol.**
-----------------------------

This plugin can be used with Jmeter to test CoAP endpoints.

There are separate samplers to test DTLS endpoints and non DTLS endpoints.


Installation Instructions:
----------------------------

1. Get the code.
2. Execute the following maven code

  > mvn dependency:copy-dependencies install -DexcludeGroupIds=org.apache.jmeter
  
3. Copy the following jars from target/dependency to  /jmeter_install_path/lib
  
  1. californium-core-1.0.0-SNAPSHOT.jar
  2. scandium-1.0.0-SNAPSHOT.jar
  3. element-connector-1.0.0-SNAPSHOT.jar
 
4. Execute the following maven code

  > mvn clean package 

5. Copy the following jar from target/ to  /jmeter_install_path/lib/ext

 1.  jmeter-coap-sampler-1.0.0.jar


  




  
  
  

  