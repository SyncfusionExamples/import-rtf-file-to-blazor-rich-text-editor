# Import RTF file in Blazor Rich Text Editor

Sample showing how to import RTF files into the Blazor Rich Text Editor using a file uploader and the uploader success event.

## Project Overview

This sample demonstrates reading an uploaded RTF file via the file uploader component, extracting the RTF content on upload success, and importing the resulting content into the Rich Text Editor for editing or display.

## Key Points

- Use file uploader to select and upload an RTF file
- Handle uploader success event to retrieve RTF content
- Import RTF content into the Rich Text Editor

## Prerequisites

- .NET 8.0 SDK
- Visual Studio 2022+ or VS Code
- Syncfusion license (if required by project packages)

## Setup & Running Steps

Installation

```bash
git clone https://github.com/SyncfusionExamples/import-rtf-file-to-blazor-rich-text-editor.git
cd import-rtf-file-to-blazor-rich-text-editor
```

Restore NuGet packages

```bash
dotnet restore
```

Run the application

```bash
dotnet run
```

## Usage

Start the app, open the importer page, use the file uploader to pick an RTF file, and on upload success the sample imports the RTF content into the editor.

## Troubleshooting

- Ensure NuGet packages are restored and the project builds before running.
- If export fails, check browser console and server logs for errors and confirm any required licenses are configured.

## Support

This sample is provided for demonstration purposes. For issues, open an issue in the repository.

## See also

- [Online examples](https://blazor.syncfusion.com/demos/rich-text-editor/overview?theme=fluent2)
- [Documentation](https://blazor.syncfusion.com/documentation/rich-text-editor/getting-started-webapp)

>Looking for the full Blazor Rich Text Editor component overview, features, pricing, and documentation? Visit the [Blazor Rich Text Editor](https://www.syncfusion.com/blazor-components/blazor-rich-text-editor) page.
