# fitbit-os-oioi
A tool to test the Fitbit OS File-Transfer API.

Device Outbox -> Companion Inbox -> Companion Outbox -> Device Inbox.

This is a tool to measure the time it takes to deliver small files over the
File-transfer API.

It will send a maximum of 4 concurrent files.
