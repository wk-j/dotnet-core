## Commands

docker build -t wearetherock/dotnet-30 .

docker run -v (pwd)/src:/app -it wearetherock/dotnet-30  bash

cd /app
dotnet new console --output src/MyApp
