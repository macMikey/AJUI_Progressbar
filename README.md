# AJUI_Progressbar

AJUI Progressbar is a component made for 4D in the V18 version that help you to create and display progress bar in your forms. You can fully customize your progress bar.

A progress bar is created via the language and will be displayed in a picture element in your form. The progress bar is stored in an object that is an instance of a progress bar.

### Lab

A lab is included within the component itself.

### Documentation

[Wiki Progressbar](https://github.com/AJARProject/AJUI_Progressbar/wiki)

**Example**

```4d
    Case of
      : (Form event=On Load)
        Form.progressBar:=New AJUI_ProgressBar

        Form.progressBar.PBPercentValue(70)
        Form.progressBar.PBPictFormObjName("progressBar_pict")
        Form.progressBar.LaunchProgressBar()

    End case
```

### Version

1.1.1-Build20  // Fri, 19 Jun 2020 14:37:42 GMT

Minimal 4D Version : 
 - 18 (using formula member function)
 - 18 R3 (using class)

### Questions?

If you have any question, you can ask them directly on github or write to info@ajar.ch
