# How to customize the header icon in .NET MAUI SfAccordion

**Repository Description**  
This repository contains a .NET MAUI sample that demonstrates how to customize the header icon in the Syncfusion **SfAccordion** control.

The sample shows how to modify the position of the header icon in an accordion item by configuring the `HeaderIconPosition` property. It provides a simple UI example using menu items such as food categories with expandable content.

## Project Overview
The purpose of this project is to help developers understand how to customize the visual layout of accordion headers in a .NET MAUI application. It focuses specifically on controlling the placement of header icons to improve UI alignment and visual clarity.

## Features
- Integration of Syncfusion .NET MAUI SfAccordion  
- Customization of accordion header icons  
- Control header icon placement using `HeaderIconPosition`  
- Use of `Start` and `End` values for icon alignment  
- Simple XAML‑based configuration  

## Prerequisites
Before running this project, ensure the following are installed:
- Visual Studio 2022  
- .NET SDK compatible with .NET MAUI  

## Installation and Running the Sample
1. Clone or download this repository.
2. Open the solution file in Visual Studio 2022.
3. Restore NuGet packages by rebuilding the solution.
4. Build and run the project on a supported MAUI target.

## About Sample

This article illustrates how to customize the header icon on [.NET MAUI SfAccordion](https://www.syncfusion.com/maui-controls/maui-accordion). In this example, we will customize the header icon on the SfAccordion.

The [SfAccordion](https://help.syncfusion.com/maui/accordion/getting-started) control is properly initialized with the necessary properties. To customize the appearance of the header icon, you can enable and set the `HeaderIconPosition` property, which allows you to change the position of the icon displayed in the header. We can set it by using `Start` and `End` values.

**XAML:**

 ```xml
   <ContentPage.Content>
    <syncfusion:SfAccordion HeaderIconPosition="Start" >
        <syncfusion:SfAccordion.Items>
            <syncfusion:AccordionItem>
                <syncfusion:AccordionItem.Header>
                    <Grid>
                        <Label TextColor="#495F6E" Text="Cheese burger" HeightRequest="50" VerticalTextAlignment="Center"/>
                    </Grid>
                </syncfusion:AccordionItem.Header>
                <syncfusion:AccordionItem.Content>
                    <Grid Padding="10,10,10,10" BackgroundColor="#FFFFFF">
                        <Label TextColor="#303030" Text="Hamburger accompanied with melted cheese. The term itself is a portmanteau of the words cheese and hamburger. The cheese is usually sliced, then added a short time before the hamburger finishes cooking to allow it to melt." HeightRequest="50" VerticalTextAlignment="Center"/>
                    </Grid>
                </syncfusion:AccordionItem.Content>
            </syncfusion:AccordionItem>
            <syncfusion:AccordionItem>
                <syncfusion:AccordionItem.Header>
                    <Grid>
                        <Label TextColor="#495F6E" Text="Veggie burger" HeightRequest="50" VerticalTextAlignment="Center"/>
                    </Grid>
                </syncfusion:AccordionItem.Header>
                <syncfusion:AccordionItem.Content>
                    <Grid Padding="10,10,10,10" BackgroundColor="#FFFFFF">
                        <Label TextColor="#303030" Text="Veggie burger, garden burger, or tofu burger uses a meat analogue, a meat substitute such as tofu, textured vegetable protein, seitan (wheat gluten), Quorn, beans, grains or an assortment of vegetables, which are ground up and formed into patties." HeightRequest="50" VerticalTextAlignment="Center"/>
                    </Grid>
                </syncfusion:AccordionItem.Content>
            </syncfusion:AccordionItem>
        </syncfusion:SfAccordion.Items>
    </syncfusion:SfAccordion>
</ContentPage.Content>
 ```

<img src="image.png" width="400">

 Download the complete sample from [GitHub](https://github.com/SyncfusionExamples/How-to-customize-the-header-icon-in-.NET-MAUI-SfAccordion)

## Usage
Run the application to observe how the accordion header icon position changes based on the `HeaderIconPosition` property. The sample demonstrates placing icons at the **start** or **end** of headers to suit layout requirements.

## Documentation
- General Syncfusion documentation:
https://help.syncfusion.com/
- .NET MAUI Introduction:
https://help.syncfusion.com/maui/introduction/overview
- .NET MAUI Accordion Getting Started:
https://help.syncfusion.com/maui/accordion/getting-started

## Additional Resources
- Syncfusion MAUI Accordion overview:
https://www.syncfusion.com/maui-controls/maui-accordion

## Troubleshooting
- Ensure Syncfusion MAUI packages are referenced correctly.
- Rebuild the solution if UI changes do not appear.
- Verify XAML namespace mappings for the accordion control.

## Support
For advanced customization options, API references, or issue resolution, refer to the Syncfusion .NET MAUI Accordion documentation links provided above.