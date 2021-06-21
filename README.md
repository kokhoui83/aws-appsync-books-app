# AWS AppSync App Example

- Validate template
```
aws cloudformation validate-template --template-body file://books-app.template
```

- Create stack
```
aws cloudformation create-stack --stack-name books-app-stack --template-body file://books-app.template --capabilities CAPABILITY_NAMED_IAM
```

- Update stack
```
aws cloudformation update-stack --stack-name books-app-stack
```

- Delete stack
```
aws cloudformation delete-stack --stack-name books-app-stack
```