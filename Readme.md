<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128609960/17.2.3%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T541476)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->

#  Rich Text Editor for WinForms - How to Customize the Pop-up Menu


The following example illustrates how to handle the [PopupMenuShowing](https://documentation.devexpress.com/windowsforms/DevExpress.XtraRichEdit.RichEditControl.PopupMenuShowing.event) event to customize the RichEditControl pop-up menus. 

![image](./media/20184abb-7026-43d2-ac95-3a369e1bb59d.png)

In the event handler, remove or disable the existing menu items, create a menu item for the RichEditControl command, and insert a custom menu item.

## Files to Review

* [Form1.cs](./CS/RichEditContextMenu/Form1.cs) (VB: [Form1.vb](./VB/RichEditContextMenu/Form1.vb))

## Documentation

* [Pop-up Menus in Rich Text Editor](https://docs.devexpress.com/WindowsForms/119048/controls-and-libraries/rich-text-editor/visual-elements/pop-up-menus)
