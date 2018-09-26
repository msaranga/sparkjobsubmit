# sparkjobsubmit

Initilize SparkArguments

 var sparkArguments = new SparkArguments();
sparkArguments.file = <<BlobLocation or SAS URL>>;
sparkArguments.className = <<SCALA CLASS NAME>>;                
sparkArguments.args = new List<string>();

 sparkArguments.args.Add("PARAM1");// 1st Argument - In scala Code, we need to access arguments by Indexes
 
