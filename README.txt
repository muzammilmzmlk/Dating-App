LoveConnect Dating Website - V32

Baseline: LoveConnect V31.

V32 update:
- Strengthened Change Password flow using Supabase Auth.
- After a successful password change, all active sessions are globally signed out.
- Login fields are cleared and the user must log in again with the new password.
- Existing V31 UI/theme and functionality are preserved.


V33: Fixed Change Password flow with current-password reauthentication, new-password verification, old-password rejection check, and cleared login fields after logout.
