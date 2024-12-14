# How-to-Customize-Content-Spacing-in-.NET-MAUI-RadioButton.
This repository contains a sample explaining how to Customize Content Spacing in .NET MAUI RadioButton.

### ContentSpacing support in .NET MAUI CheckBox.

The `ContentSpacing` feature in RadioButton control allows for flexible adjustment of the space between the control's visual element and its associated label text.

The following code example illustrate how to set ContentSpacing in SfRadiButton.

### XAML

```
    <StackLayout Padding="20">
        <Label Text="Select a fruit"/>
        <syncfusion:SfRadioGroup>
        <syncfusion:SfRadioButton Text="Papaya" 
                 ContentSpacing="15" 
                 IsChecked="True" 
                 HorizontalOptions="Start"/>

        <syncfusion:SfRadioButton Text="Apple"
                 ContentSpacing="25" 
                 IsChecked="False" 
                 HorizontalOptions="Start"/>

        <syncfusion:SfRadioButton Text="Banana"
                 ContentSpacing="5" 
                 IsChecked="False" 
                 HorizontalOptions="Start"/>

        <syncfusion:SfRadioButton Text="Orange"
                 ContentSpacing="10" 
                 IsChecked="False" 
                 HorizontalOptions="Start"/>

        <syncfusion:SfRadioButton Text="Pineapple"
                 ContentSpacing="20" 
                 IsChecked="False" 
                 HorizontalOptions="Start"/>
        </syncfusion:SfRadioGroup>
    </StackLayout>

```

### C#

```
    SfRadioButton radioButton = new SfRadioButton();
    radioButton.Text = "Papaya";
    radioButton.ContentSpacing = 25;

```