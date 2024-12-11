# How-to-Customize-Content-Spacing-in-.NET-MAUI-RadioButton.
This repository contains a sample explaining how to Customize Content Spacing in .NET MAUI RadioButton.

### ContentSpacing support in .NET MAUI CheckBox.

The `ContentSpacing` feature in RadioButton control allows for flexible adjustment of the space between the control's visual element and its associated label text. This feature enhances layout customization by offering different spacing options, ensuring that UI components are aligned according to design preferences.

The following code example illustrate how to set ContentSpacing in SfRadiButton.

### XAML

```
    <syncfusion:SfRadioButton Text="Radio Button" ContentSpacing="25"/> 

```

### C#

```
    StackLayout stackLayout = new StackLayout();
    SfRadioButton radioButton = new SfRadioButton();
    radioButton.Text = "Radio Button";
    radioButton.ContentSpacing = 25;
    stackLayout.Children.Add(radioButton);
    this.Content = stackLayout; 

```