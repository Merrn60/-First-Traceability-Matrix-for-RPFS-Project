# First Traceability Matrix for RPFS Project

## Purpose
This matrix ensures traceability by linking functional (FRs) and non-functional (NFRs) requirements to their corresponding tasks, test IDs, status, priority, and related requirements.

| **Requirement ID** | **Requirement Description** | **Task ID** | **Test ID** | **Status** | **Priority** | **Linked/Related** |
|--------------------|-----------------------------|-------------|-------------|------------|--------------|--------------------|
| FR001 | User can Create account with name, password, and email | RPFS-1 | T001 | Done | Highest | Linked to FR002 |
| FR002 | User Login using name and password | RPFS-2 | T002 | Done | High | Linked to FR001, FR016 |
| FR003 | User Book order with home delivery | RPFS-4 | T004 | Done | Medium | Linked to FR003, FR007 |
| FR004 | User can Display price while selecting a gift | RPFS-5 | T003 | Done | Medium | Linked to FR005, FR004 |
| FR005 | User Choose from multiple options | RPFS-6 | T008 | Done | Highest | Linked to FR007 |
| FR006 | User Place multiple orders | RPFS-7 | T007 | Done | Medium | Linked to FR008, FR020 |
| FR007 | User Write comments and wishlist items | RPFS-8 | T005 | Done | High | Linked to FR003, FR008 |
| FR008 | User Provide ratings | RPFS-9 | T009 | Done | Highest | Linked to FR007, FR008 |
| FR009 | Manager views user feedback | RPFS-10 | T006 | Done | Highest | Linked to FR020 |
| FR010 | User Show purchase details (e.g., discount, item count) | RPFS-11 | T013 | Done | Highest | Linked to FR014, FR018 |
| FR011 | Manager can Modify product details (e.g., price, quantity) | RPFS-12 | T014 | Done | Highest | Linked to FR013, FR022 |
| FR012 | Decrease product quantity on order | RPFS-13 | T010 | Done | Highest | Linked to FR015, FR016 |
| FR013 | View customer orders for preparation | RPFS-14 | T012 | Done | Highest | Linked to FR011 |
| FR014 | Contact customers about order details | RPFS-15 | T011 | Done | Highest | Linked to FR012, FR022 |
| FR015 | Calculate total cart price | RPFS-16 | T015 | Done | Highest | Linked to FR016, FR017 |
| FR016 | Apply discount and calculate final price | RPFS-17 | T018 | Done | Highest | Linked to FR002, FR015, FR018 |
| FR017 | Add final price to receipt | RPFS-18 | T016 | Done | High | Linked to FR015 |
| FR018 | Reset password if forgotten | RPFS-19 | T017 | Done | Highest | Linked to FR016, FR010 |
| FR019 | Cancel orders | RPFS-20 | T019 | In Progress | High | Linked to FR020 |
| FR020 | Update orders by changing quantity | RPFS-21 | T020 | In Progress | Highest | Linked to FR006, FR019 |
| FR021 | Manager Add new products (name, price, quantity) | RPFS-22 | T021 | In Progress | High | Linked to FR011 |
| FR022 | Delete products | RPFS-23 | T022 | Done | Highest | Linked to FR011, FR014 |
| NFR001 | Ensure accessibility (ADA compliance, colorblind-friendly) | RPFS-24 | T023 | In Progress | Highest | Universal access |
| NFR002 | Ensure intuitive and user-friendly design | RPFS-25 | T024 | In Progress | Highest | Universal access |
| NFR003 | Ensure system performance under heavy load | RPFS-26 | - | In Progress | Medium | - |
| NFR004 | Ensure system security for sensitive data | RPFS-27 | T025 | In Progress | Highest | Universal access |

## Notes
- **Coverage**: All functional requirements (FRs) have associated test IDs except NFR003, indicating testing is not yet complete for this requirement.
- **Status**: 73.1% of tasks (19 out of 26) are completed, with 26.9% (7 tasks) in progress, primarily in Sprint 5.
- **Linkages**: Requirements are highly interconnected, indicating dependencies (e.g., FR015, FR016, and FR017).
- **Recommendations**: Prioritize completing in-progress tasks in Sprint 5, especially NFR001 and NFR004, due to their high priority.
