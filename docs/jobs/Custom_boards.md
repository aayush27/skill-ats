---
title: Custom boards
---

# Custom boards

A **custom board** is a pipeline that is **not linked to a job**. Use it to organise candidates by project, talent pool, internal process, or any flow that does not need a published role.

Job boards and custom boards share the same drag-and-drop layout. For full board actions (search, filters, stages, cards), see [The hiring board](Candidates_board.md).

## Job board vs custom board

| | **Job board** | **Custom board** |
|---|----------------|------------------|
| Linked to a job | Yes | No |
| Created from | Creating / opening a job | Dashboard → **Custom Boards** → **Add board** |
| **Edit Job** | Available | Not available |
| Career site applications | Can land here | Does not receive job applications |
| Job tests | Can be configured on the job | No job tests |
| Special stage actions | Available (see below) | **Not available** |

## When to use a custom board

- Shortlisting for a project before a formal job exists
- A shared talent pool or “warm leads” pipeline
- Internal tracking that should not appear as a published job
- Organising people across themes that are not one-to-one with a single opening

If you need applications from the career site, assessments tied to a role, or automatic test/reject behaviour, create a **job** and use its [hiring board](Candidates_board.md) instead.

## How to create and open one

1. Go to the [dashboard](../getting_started/Dashboard.md).
2. Find the **Custom Boards** section.
3. Click **Add board**.
4. SkillATS opens the new board so you can rename it, set stages, and add candidates.

You can also search custom boards on the dashboard, open an existing one, or delete a board you no longer need (with confirmation).

## What works the same as a job board

On a custom board you can still:

- Drag candidates between stages
- Add candidates to the board or into a specific stage
- Search and filter
- Rename the board and manage stages (add, rename, reorder, remove)
- Open a candidate card for notes, reminders, status, and other details
- Use **Activity** on the board

Default stage names still come from **Settings → Recruitment stages**, and you can change them on the board. See [The hiring board](Candidates_board.md).

## What does *not* work on custom boards

Because there is **no job** behind a custom board, job-linked stage behaviour is off:

### Send tests automatically (assignment / assessment)

On a **job board**, a stage can use **Send tests automatically** so moving someone there can email the job’s tests (often used with a stage like **Assessment Assigned** / **Assignment Assigned**).

On a **custom board**:

- There are no job tests to send
- The **Send tests automatically** option does not appear in the stage menu
- Dragging someone into a stage named “Assessment Assigned” (or similar) does **not** send tests

To assign assessments, use a [job board](Candidates_board.md) with tests configured on that job.

### Reject stage (automatic rejection email)

On a **job board**, dragging someone into a stage named **Rejected** or **Reject** can offer an **automatic rejection email** using the job’s email template.

On a **custom board**:

- There is no job rejection template to send from
- That special reject-email flow does not apply the way it does on job boards
- You can still keep a stage called Rejected for your own organisation, and set status on the [candidate page](../candidates/Candidate_record.md), but do not expect the job-style automatic rejection email from this board

### Edit Job and career applications

- **Edit Job** is hidden on custom boards
- Candidates do not apply into a custom board from the [career site](../career/Public_career_site.md) — applications go to job boards

## Tips

- Use custom boards for flexible pipelines; use job boards when you need the full hiring role (posting, tests, reject email, applications).
- You can [copy or move](../candidates/Candidate_record.md#copy-card) a candidate between a custom board and a job board when the process becomes a real opening.
- For stage menus, dragging, and filters in detail, continue on [The hiring board](Candidates_board.md).
