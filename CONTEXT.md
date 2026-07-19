# Family Photo Sharing

This context covers the private publication of one curator's photos and videos to selected family members.

## Language

**Curator**:
The sole Person with authority to publish media and control who may access it. Curator is a role on a Person, and that same Person may also be a Recipient rather than having a separate identity.
_Avoid_: Publisher, admin, photographer

**Recipient**:
A Person who has been invited to receive access to published media but does not publish or manage sharing. Each Recipient is exactly one Person; invitation, email, session, and access changes do not create or replace that Person.
_Avoid_: User, viewer, contributor

**Person**:
A family member who may attend a moment, whether or not they are a Recipient. A Person persists independently of invitation status, login access, and email address.
_Avoid_: Contact, profile, face

**Attendance**:
The curator-confirmed people who were present at a moment; face detections may suggest people but are not authoritative.
_Avoid_: Detected faces, appearances

**Interest list**:
The People explicitly chosen by a Recipient, or by the Curator on that Recipient's behalf, whose Attendance should cause that Recipient to be suggested for a Moment. Choices are limited to People visible through shared Visibility circles. Either may edit the list, and every change is attributed to the Person who made it and retained in an audit history. Family changes may provide new choices but never alter the list automatically; losing shared visibility deactivates an ineligible choice without erasing its history. It influences an Audience proposal but never grants access.
_Avoid_: Permissions, subscriptions, access list

**Family relationship**:
An explicit parent-child, current-partner, or sibling connection between People. Sibling connections may be recorded even when their shared parents are absent; they annotate People choices but do not seed a Family branch.
_Avoid_: Account relationship, inferred relationship

**Visibility circle**:
A Curator-managed, overlapping set of People that determines whom a Recipient may discover and choose for their Interest list. A Recipient may discover the union of People in every circle containing their own Person; membership is not transitive across circles and never grants media access.
_Avoid_: Bubble, group, Audience

**Family branch**:
A Person's current partners, every descendant, and every descendant's current partners recursively through all generations. It provides relationship-annotated choices for that Recipient's Interest list but never adds them without explicit opt-in. Siblings and their descendants are not included automatically.
_Avoid_: Immediate family, household

**Event**:
A narrative container for related photos and videos, which may contain moments with different audiences.
_Avoid_: Album, gallery

**Moment**:
A curator-only part of an event with one audience, often used where attendance changes; recipients see one filtered event rather than its moment boundaries.
_Avoid_: Sub-album, segment

**Loose item**:
A photo or video shared independently rather than through an event.
_Avoid_: One-off, loose photo

**Audience proposal**:
The system's suggested Recipients for a Moment, based on Attendance, Interest lists, or Curator choices, which becomes an Audience only after Curator approval. The Curator never appears in a proposal because Curator authority already provides access.
_Avoid_: Automatic sharing, recipient list

**Audience**:
The approved recipients allowed to access a moment or loose item.
_Avoid_: Members, invitees

**Publication**:
The curator's approval that makes an event or subsequent update visible to its audiences.
_Avoid_: Sync, import

**Staged update**:
The single coalescing set of source-library changes to a published event that remains private until the curator publishes it.
_Avoid_: Live sync, pending upload

**Notification preference**:
A Recipient's choice to receive publication emails immediately, in a weekly digest, or not at all. Publication and activity notifications do not begin until the Recipient completes onboarding.
_Avoid_: Access preference, subscription

**Favorite**:
A recipient's personal selection of a photo or video, visible to that recipient and the curator but hidden from other recipients.
_Avoid_: Like, reaction, public favorite

**Comment**:
A message on a photo or video, visible only to the curator and recipients who can access that item.
_Avoid_: Event comment, public comment
