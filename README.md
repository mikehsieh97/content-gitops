### Hands-On HitHub GitOps Lab

* Create Docker hub secret under content-gitops repo => 
`
On GitHub, navigate to content-gitops repo.
Click Settings.
In the left sidebar, click Secrets.
Click New secret.
Type a name for your secret in the Name input box. => Use "DOCKERPW"
Enter the Value for your secret. => my dockerhub password
From the Repository access dropdown list, choose an access policy.
Click Add secret.
`

* Update content-gitops/.github/workflows/pythonapp.yml

