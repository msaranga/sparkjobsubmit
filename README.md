# sparkjobsubmit

Initilize SparkArguments

 var sparkArguments = new SparkArguments();
sparkArguments.file = <<BlobLocation or SAS URL>>;
sparkArguments.className = <<SCALA CLASS NAME>>;                
sparkArguments.args = new List<string>();

 sparkArguments.args.Add(wrkGenericSelectQuery);// 1st Argument - Select query from wrkGeneric_pq
  sparkArguments.args.Add("true");  
