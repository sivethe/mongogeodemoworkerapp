# Demo WorkerRole Azure Cloud Service 
WorkerRole to perform latency measurement in Azure Cloud Service for **Mongo API Support** powered by **Azure DocumentDB**

* Config required:
 * Add correct account credentials in WorkerRole.cs.

* Details:
 * Uses  C# Mongo SDK
 * Uses read preference = NEAREST for read latency measurement
 * Write latency is measured only from write region
 
* The Front end web app to visualize latencies is deployed [here](http://mongogeodemo.azurewebsites.net/)
* The source code for frontend web app is [here](https://github.com/vidhoonv/mongogeodemowebapp)