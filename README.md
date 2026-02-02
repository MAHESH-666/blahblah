# blahblah
# blah-blah
alpha
beta
Request and Response
Qualcomm...
xzcxzcxzc
xzxzccx
xzczxxz
xz
zx
zxUSE HelpDeskManagement;
GO

BEGIN TRANSACTION;

delete from HD_TicketLink
-- Activities
DELETE FROM HD_MaintenanceTicketActivity;

-- Notifications
DELETE FROM HD_MaintenanceNotification;

-- Attachments
DELETE FROM HD_MaintenanceAttachment;

-- Comments
DELETE FROM HD_MaintenanceTicketComment;

-- Vendors
DELETE FROM HD_MaintenanceTicketVendor;

-- PRs (Maintenance)
DELETE FROM HD_TicketPR
WHERE MaintenanceTicketID IS NOT NULL;

DELETE FROM HD_MaintenanceTicket;

------------------------------------------------

-- Activities
DELETE FROM HD_TicketActivity;

-- Notifications
DELETE FROM HD_Notification;

-- Attachments
DELETE FROM HD_Attachment;

-- Comments
DELETE FROM HD_TicketComment;

-- Vendors
DELETE FROM HD_TicketVendor;

-- PRs (IT)
DELETE FROM HD_TicketPR
WHERE ITTicketID IS NOT NULL;

DELETE FROM HD_Ticket;

UPDATE HD_TicketSequence
SET LastNumber = 0;

COMMIT TRANSACTION;

GO

cx
zc
xz
czx
c
xz
xz
xz
xz

cz
