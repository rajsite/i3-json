# i3-json

The i3 JSON Toolkit is used to parse and generate arbitrary JSON data in LabVIEW. The toolkit allows the user to manipulate JSON data following the specification described at json.org and in RFC 4627.

An API interface consisting of a set of low-level and fast VIs are provided for the development of applications as well as a set of high-level and slow VIs to enable rapid prototyping. Utilities for visualizing JSON data in LabVIEW Trees are made available for user interaction.

## Error Codes
The i3 JSON Toolkit has 538900 - 538950 reserved, and currently uses the following error codes:

| Error Code | Error Name | Description |
| ---------- | ---------- | ----------- |
| 538900 | Parse Error | This is thrown when the JSON String parse fails |
| 538901 | Create Error | This is thrown when the generation of a JSON Object fails |
| 538902 | Conversion Error | This is thrown when a given JSON Object cannot be converted to a given type |
| 538904 | Invalid Type Error | The given value is not a compatible type for the JSON Object |
| 538905 | Not Found Error | The given parameter cannot be found in the JSON Tree |