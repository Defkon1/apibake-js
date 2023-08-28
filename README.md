# ApiBake

REST API PDF creator from OpenAPI .json or .yaml files. Supports OpenAPI 3.0.0 spec. 

**Usage**: apibake <openapi.json|.yaml|folder-name> [<file-or-folder2> <file-or-folder3> ...] [<options>]

**Options**:
 -output <string>: Output file.
 -title <string>: Document title.
 -subtitle <string>: Document sub title.
 -separate-schemas: When multiple API files parsed create separate schemas section for each file.
 -help: Show this help page.