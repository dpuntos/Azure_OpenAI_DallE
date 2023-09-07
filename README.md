# AzureOpenAIDallE
A C# Azure function wich uses Azure OpenAI services and Dall·E integration.
## Description
This Azure Function allows you to send a description as a parameter in the URL. The result is an image generated by Dall·E using the indicated description.
<br><br>
For example:<br><h5>
>https://{resourceName}.azurewebsites.net/api/Function1?code={api_key}==&desc=a portrait of a ninja cat painted in Van Gogh style
</h5><br>
The function receives the description. Finally, the generated image by Dall·E is obtained through the integration with Azure OpenAI services.
<p align="center">
  <img src="../master/sample_img.png">
</p>

## Diagram
<p align="center">
  <img src="../master/Diagram.png">
</p>

> [!NOTE]
> - Azure Open AI DALL·E playground is in Preview mode.
> - Azure account must have access to Azure OpenAI services.
