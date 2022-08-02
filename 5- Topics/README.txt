Para recibir todos los logs:
	cd ReceiveLogsTopic
	dotnet run "#"

Para recibir todos los registros desde la instalacion "kern":
	cd ReceiveLogsTopic
	dotnet run "kern.*"

Si querés escuchar solo critical logs:
	cd ReceiveLogsTopic
	dotnet run "*.critical"

Para crear multiples bindings:
	cd ReceiveLogsTopic
	dotnet run "kern.*" "*.critical"

Para emitir logs con una clave de enrutamiento del tipo "kern.critical":
	cd EmitLogTopic
	dotnet run "kern.critical" "A critical kernel error"