# azure-asp-api

dotnet build

docker build -t azure-asp-api .

docker run azure-asp-api

docker tag azure-asp-api dillostestregistry.azurecr.io/dillos/azure-asp-api

docker push dillostestregistry.azurecr.io/dillos/azure-asp-api