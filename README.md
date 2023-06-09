# Pricing_API

## Reference

[githubSite](https://github.com/afairi-yifan/car_warranty_pricing.git)

[VertaxAI_tutorial](https://github.com/afairi-yifan/car_warranty_pricing.git)

## Questions

1. What framework (tensorflow or pytorch) we are currently using?
2. api in the docker, do you mean put the endpoint to a docker container? 
3. From the draw.io, how to put docker container inside of vertex AI?
4. what machine learning model to be deployed?

## Structure

Online prediction to perform synchronous, low-latency response from our Vertax API prediction. 

1. Upload the model to the Registry
2. Provide the model to the endpoint.
3. Create online prediction based from the input.

### Testing model locally

Reference and work on the local model in this [notebook](https://github.com/GoogleCloudPlatform/vertex-ai-samples/blob/main/notebooks/community/vertex_endpoints/find_ideal_machine_type/find_ideal_machine_type.ipynb)


### Why?”; “What?”; “How?

mlops: ML [pipeline ins Vertex AI](https://cloud.google.com/vertex-ai/docs/pipelines/introduction)



[customDocker](https://github.com/GoogleCloudPlatform/vertex-ai-samples/blob/main/notebooks/official/custom/sdk-custom-image-classification-online.ipynb)


Google Cloud.
https://console.cloud.google.com/vertex-ai/models?project=car-warranty-01

## Step 

1. Create and test the pricing model with docker image locally. 
2. Update the pricing model to the vertexAI.
3. Create online prediction piles and workflow to render the results from Model. 

