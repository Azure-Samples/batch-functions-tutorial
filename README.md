# Trigger a Batch job using Azure Functions

The files in this repo are used in conjunction with our [Batch-Functions OCR tutorial](https://docs.microsoft.com/azure/batch/tutorial-batch-functions), which shows how to trigger Batch jobs based off a blob-triggered Function.

Use the following files to create your Function:

   * `run.csx`, which is run when a new blob is added to your input blob container.
   * `function.proj`, which lists the external libraries in your Function code, for example, the Batch .NET SDK.

We've also provided `function.json`, which describes the bindings for your Function. This should be generated automatically and is given here for reference.

Use the scanned documents available in `input_files` to test your OCR pipeline.
