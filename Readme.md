# Room Booking Application Documentation

## Overview

This document provides details about the SharePoint lists used in the Room Booking Application. The application leverages two main lists to manage room bookings and admin functions, and integrates with various connectors to enhance its functionality.

## SharePoint Lists

### List 1: Room Booking Details .

This list stores the information related to room bookings.

| **Column Name**   | **Type**               | **Description**                                  |
| ----------------- | ---------------------- | ------------------------------------------------ |
| **BookedByEmail** | Single line of text    | Email address of the person who booked the room. |
| **BookedByName**  | Single line of text    | Name of the person who booked the room.          |
| **RoomName**      | Single line of text    | Name of the room that has been booked.           |
| **RoomEmail**     | Single line of text    | Email address of the room that has been booked.  |
| **StartTime**     | Single line of text    | Start time of the booking.                       |
| **EndTime**       | Single line of text    | End time of the booking.                         |
| **MeetingID**     | Multiple lines of text | Identifier for the meeting or event.             |

### List 2: Room Booking App Admin

This list is used for managing administrative users of the Room Booking application.

| **Column Name** | **Type**                      | **Description**          |
| --------------- | ----------------------------- | ------------------------ |
| **Username**    | People picker (single select) | User profile information |

## Connectors Used

| **Connector Name**     |
| ---------------------- |
| **Office 365 Outlook** |
| **Office 365 Users**   |
| **SharePoint**         |
