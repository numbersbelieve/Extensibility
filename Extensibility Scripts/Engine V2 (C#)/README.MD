## Folder Contents
This folder contains code samples for the C# version of the cloud extensibility engine of the platform.

## File Descriptions

### LoadCommitmentsFromDifferentInteraction.cs
 Queries the platform's API to obtain data on a commitment to fill a commitment in a different interaction.

### FillAttributesFromExternalAPI.cs
Obtains data from an external API and fills document parameters with it. Should be executed on an "On Change" action on the document's Code.

### FillListFromExternalApi.cs
Obtains data from an external API and fills a list with it. Used as the query script in an External Entity, set to run as Local.

### RedirectToCreate.cs
Redirects to the page for creating an entity of type Person, passing it a parameter from the current entity.