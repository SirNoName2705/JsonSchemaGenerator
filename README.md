# Visual Studio 2022:
There should be an Option somewhere in the ide to add a custom json catalog.
Tools>Options>Json>Schema
Then click add new one in the upper left.
Copy this link: `https://raw.githubusercontent.com/SirNoName2705/JsonSchemaGenerator/master/SchemaDirectOutput/vs_schema_catalog.json`
and paste it in the settings.
Save and restart the ide.

## Workaround
- https://devblogs.microsoft.com/dotnet/intellisense-for-json-schema-in-the-json-editor/

# Rider
- Download the JsonSchemas.xml of your choice. (url or local version)
- Then put it in the .idea/.idea.__ProjectName__.dir/.idea folder (that is the .idea folder of the project not the solution)
- If you use the local version you also need to put the .schemas folder in the main directory

# VScode
- Download the JsonSchemas.xml of your choice. (url or local version)
- Put the file in your .vscode folder
- If you use the local version you also need to put the .schemas folder in the main directory




Credits:
- DarkhNekromant for the idea and a lot of the code.
