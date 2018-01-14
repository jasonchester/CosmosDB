---
external help file: CosmosDB-help.xml
Module Name: CosmosDB
online version: 
schema: 2.0.0
---

# Set-CosmosDbStoredProcedure

## SYNOPSIS
Update a stored procedure from a CosmosDB collection.

## SYNTAX

### Connection (Default)
```
Set-CosmosDbStoredProcedure -Connection <Connection> [-Database <String>] [-Key <SecureString>]
 -CollectionId <String> -Id <String> -StoredProcedureBody <String> [<CommonParameters>]
```

### Account
```
Set-CosmosDbStoredProcedure -Account <String> [-Database <String>] [-Key <SecureString>] [-KeyType <String>]
 -CollectionId <String> -Id <String> -StoredProcedureBody <String> [<CommonParameters>]
```

## DESCRIPTION
This cmdlet will update an existing stored procedure in a CosmosDB
collection.

## EXAMPLES

### Example 1
```
PS C:\> {{ Add example code here }}
```

{{ Add example description here }}

## PARAMETERS

### -Connection
This is an object containing the connection information of
the CosmosDB database that will be deleted.
It should be created
by \`New-CosmosDbConnection\`.

```yaml
Type: Connection
Parameter Sets: Connection
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Account
The account name of the CosmosDB to access.

```yaml
Type: String
Parameter Sets: Account
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Database
The name of the database to access in the CosmosDB account.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Key
The key to be used to access this CosmosDB.

```yaml
Type: SecureString
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -KeyType
The type of key that will be used to access ths CosmosDB.

```yaml
Type: String
Parameter Sets: Account
Aliases: 

Required: False
Position: Named
Default value: Master
Accept pipeline input: False
Accept wildcard characters: False
```

### -CollectionId
This is the Id of the collection to update the stored procedure for.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Id
This is the Id of the stored procedure to update.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -StoredProcedureBody
This is the body of the stored procedure.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

### System.Object

## NOTES

## RELATED LINKS
