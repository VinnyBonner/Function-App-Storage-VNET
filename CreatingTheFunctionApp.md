# In this page, we will go over creating the Function App. | En esta página, repasaremos la creación de la aplicación Function.

The first step is to create a simple Function App via the Azure Portal. | El primer paso es crear una aplicación de función sencilla a través del Portal de Azure.

![image](https://user-images.githubusercontent.com/92878154/208965566-35b095f7-ebaf-49a3-880a-99fb45358fa5.png)
#### Region: It is best to keep the Region of the Function App, Storage account and VNET all in the same Region. 
#### Región: es mejor mantener la región de la aplicación de función, la cuenta de almacenamiento y la red virtual en la misma región.

![image](https://user-images.githubusercontent.com/92878154/208965689-3ffecdd9-e245-4508-bd6d-d499022ad4d9.png)
#### Plan: That only Functions Premium (Elastic Premium) and App Service Plan support VNET integration, Consumption Plans do not.
#### Plan: que solo Functions Premium (Elastic Premium) y App Service Plan admiten la integración de redes virtuales, los planes de consumo no.

![image](https://user-images.githubusercontent.com/92878154/208965732-251ff523-5231-455e-9697-832110e57047.png)
#### Storage Account: It is recommended that the Storage account is only used by the single Function App and not multiple Function Apps. 
#### Cuenta de almacenamiento: se recomienda que la cuenta de almacenamiento solo la use la aplicación de función única y no varias aplicaciones de función.

![image](https://user-images.githubusercontent.com/92878154/208965781-60a61e16-b5c7-4a76-969c-dc9f6eba5c38.png)
#### Networking: We will manually create the VNET and integrate it. So for now, don't Enable network Injection.
#### Redes: crearemos manualmente la red virtual y la integraremos. Entonces, por ahora, no habilite la inyección de red.

![image](https://user-images.githubusercontent.com/92878154/208965941-7a5f2d07-d7b5-4f13-b8d3-33015cb1cf65.png)
#### Application Insights: I highly recommend setting up Application Insights. However, for this tutorial I will not be setting it up. 
#### Application Insights: Recomiendo encarecidamente configurar Application Insights. Sin embargo, para este tutorial no lo configuraré. 

![image](https://user-images.githubusercontent.com/92878154/208966051-74ae27a1-266d-45d3-8d13-7c9ddda2b92a.png)
#### Tags: You can add any Tags here. There are various reasons to use Tags.
#### Etiquetas: Puede agregar cualquier etiqueta aquí. Hay varias razones para usar etiquetas.

![image](https://user-images.githubusercontent.com/92878154/208966270-9a9de90b-8009-4a01-bd85-0e6f64453f8e.png)
#### Template: If you wish, you can download the ARM template for use in automation. Otherwise, you can click Create.
#### Plantilla: Si lo desea, puede descargar la plantilla ARM para su uso en automatización. De lo contrario, puede hacer clic en Crear.





