# EduYield — Learn-to-Earn Stacks Contract

Simple learn-to-earn Clarity contract for the Stacks blockchain. Students stake a fee to enroll in a course, submit a quiz, and if they pass they can claim their reward plus their stake.

Contract file:
c:\Users\USER\Desktop\STACKS\OCTOMBER\eduyield\contracts\eduyield.clar

## Features
- Admin controls (set admin, create/deactivate courses)
- Course storage: title, instructor, reward, fee, active
- Enrollment storage: staked amount, completion flag, score
- Student flows: enroll (stakes fee), submit-quiz (pass threshold u50), claim-reward (payout + stake)
- Read-only getters for courses, enrollments, total courses, and admin
- Explicit error codes for common failures

## Quick usage
Prereqs: Clarinet or Stacks CLI, Node.js (optional), a local Stacks testnet.

Compile & run tests (Clarinet):
```bash
cd c:\Users\USER\Desktop\STACKS\OCTOMBER\eduyield
clarinet test
