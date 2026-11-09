# Accès aux logiciels

## Java
Vérifier l'installation :
```powershell
java -version
```

## Maven
Maven est accessible avec le wrapper du projet :
```powershell
.\mvnw.cmd -version
```

## PostgreSQL

Vérifier que le service fonctionne :
```powershell
Get-Service postgresql-x64-18
```

Accéder à PostgreSQL :
```powershell
& "C:\postgresql\bin\psql.exe" -U postgres -h localhost -p 5432 -d postgres
```

## Visual Studio Code

Ouvrir le projet :
```powershell
code .
```

## Git

Vérifier la version :
```powershell
git --version
```