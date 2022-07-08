# gitchartrepo

helm create demochart

helm package demochart

helm repo index . //creates the index file with details of demochart
  
</br>
</br>
For pull or install:

helm pull gitrepo/demochart

helm install gitapp gitrepo/demochart
