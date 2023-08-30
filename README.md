# SharePoint 'Time to read'

| [Solution Overview](https://github.com/alexc-MSFT/spo-timetoread/wiki/Solution-Overview) | [Deployment](https://github.com/alexc-MSFT/spo-timetoread/wiki/Deployment) |
| ---- | ---- |

This solution allows you to display an estimated read time (Time to read) on modern SharePoint pages. It uses the Power Platform (Power Automate) to achieve this and is typically designed for Intranet/Viva Connections scenarios. This has been a common ask from many of my customers so I decided to make it into a reusable solution.

It comprises of a single Power Automate flow coupled with two additional columns added to the 'Site Pages' library (either directly OR via Content Types). 

The 'Page Properties' Web Part is used to display the time to read on the page itself. 

All content on the page is counted when estimating the time to read including Web Parts.

![Time to read on SharePoint modern news page](https://github.com/alexc-MSFT/spo-timetoread/assets/12395485/6859e6f8-3e0a-4e72-81be-1ce8fbbfcddc)

## Getting started

Begin with the [Solution overview](https://github.com/alexc-MSFT/spo-timetoread/wiki/Solution-Overview) to read more about the solution and how it works. 

When you're ready to try it out, or to use it in your own tenant, follow the [Deployment](https://github.com/alexc-MSFT/spo-timetoread/wiki/Deployment) steps. Please note the deployment steps assume a level of technical knowledge and are relatively high level.

## 💖 Contributing 

Please feel free to contribute to this solution or fork this project for your own needs.
