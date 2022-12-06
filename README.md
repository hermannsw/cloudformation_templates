* Create
```
aws cloudformation create-stack --stack-name my-stack --template-body file://template.yaml --capabilities CAPABILITY_NAMED_IAM
```

* Update
```
aws cloudformation update-stack --stack-name my-stack --template-body file://template.yaml --capabilities CAPABILITY_NAMED_IAM
```

* Delete
```
aws cloudformation delete-stack --stack-name my-stack
```

* Validate Template
```
aws cloudformation validate-template --template-body file://template.yaml
```

https://docs.aws.amazon.com/ja_jp/ses/latest/dg/send-email-concepts-credentials.html
https://docs.aws.amazon.com/ja_jp/AWSCloudFormation/latest/UserGuide/intrinsic-function-reference-getatt.html
https://docs.aws.amazon.com/ses/latest/dg/control-user-access.html#iam-and-ses-examples-email-sending-actions
https://docs.aws.amazon.com/ja_jp/AWSCloudFormation/latest/UserGuide/aws-resource-ses-emailidentity.html
https://docs.aws.amazon.com/ja_jp/AWSCloudFormation/latest/UserGuide/aws-properties-route53-recordset.html
