Introduction to the Terraform Output Block

Terraform output values allow you to export structured data about your resources. 
You can use this data to configure other parts of your infrastructure with automation tools, or as a data source for another Terraform workspace. 
Outputs are also necessary to share data from a child module to your root module.

As with all other blocks in HashiCorp Configuration Language (HCL), the output block has a particular syntax that needs to be followed when creating output blocks.
Each output name should be unique. The syntax looks like this:


    1: Add Output Block to Export Attributes of Resources
    2: Output Meaningful Data using Static and Dynamic Values
    3: Generate Machine-Readable Outputs in JSON
