# Data Design

The system database contains several core entities.

## User

Stores user account information and roles.

## Role

Defines system permissions such as requester, staff, and manager.

## ServiceRequest

Stores request details including title, description, priority, and status.

## Category

Defines request categories such as IT support or facility maintenance.

## Comment

Allows staff and users to communicate through request comments.

## StatusHistory

Tracks changes to request status over time.

## Attachment

Stores files uploaded with service requests.
