# AWS AppSync App Example

- Validate template
```
aws cloudformation validate-template --template-body file://books-app.template.yaml
```

- Create stack
```
aws cloudformation create-stack --stack-name books-app-stack --template-body file://books-app.template.yaml --capabilities CAPABILITY_NAMED_IAM
```

- Update stack
```
aws cloudformation update-stack --stack-name books-app-stack --template-body file://books-app.template.yaml --capabilities CAPABILITY_NAMED_IAM
```

- Delete stack
```
aws cloudformation delete-stack --stack-name books-app-stack
```

#### Note
- Subscriptions response cannot be mandatory field