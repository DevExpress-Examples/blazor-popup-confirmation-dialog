<!-- default badges list -->
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T1183417)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
# Popup for Blazor - How to implement a confirmation dialog

This example demonstrates how to use [Blazor Popup](https://docs.devexpress.com/Blazor/404363/components/dialogs-and-windows#popup) to create a [custom confirmation dialog](https://docs.devexpress.com/Blazor/404363/components/dialogs-and-windows/popup-based-confirmation-dialog) for delete operations in [Blazor Scheduler](https://docs.devexpress.com/Blazor/401179/components/scheduler).

![DxPopup - Confirmation dialog](ConfirmationDialog.png)

## Overview

Follow the steps below to implement a confirmation dialog:

1. Add the [DxPopup](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxPopup) component to the page, configure its user functionality, and add custom buttons the component's content area.

2. Handle the [DxSxheduler](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxScheduler) component's [AppointmentRemoving](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxScheduler.AppointmentRemoving) event to display a confirmation dialog when a user deletes an appointment.

3. Create a [task](https://learn.microsoft.com/en-us/dotnet/api/system.threading.tasks.taskcompletionsource-1?view=net-7.0) that deletes an appointment or cancels the current delete operation on the corresponding button click.

## Files to Review

- [ConfirmationDialog.razor](CS/Pages/ConfirmationDialog.razor)
- [Index.razor](CS/Pages/Index.razor)

## Documentation

- [Implement a Confirmation Dialog Based on Blazor Popup](https://docs.devexpress.com/Blazor/404363/components/dialogs-and-windows/popup-based-confirmation-dialog)
- [DxScheduler - Manage Appointments](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxScheduler?#manage-appointments)
