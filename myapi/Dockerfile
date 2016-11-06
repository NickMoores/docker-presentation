FROM corertm

COPY . /app
WORKDIR /app

RUN ["dotnet", "restore"]

EXPOSE 5000/tcp

ENTRYPOINT ["dotnet", "run"]
