# Go Live Without M1

## Steps to Follow

1. **Create a New Staging Branch**
   - Create a new branch named `old-v(version)` in your staging environment.

2. **Backup the Main Database**
   - Ensure that you take a complete backup of the main database.

3. **Add Cluedoo Submodule**
   - Using `odoo.sh`, add the Cluedoo submodule to the main database.

4. **Upgrade the Main Database**
   - Start upgrading the main database.
   - When prompted, push an empty commit to initiate the upgrade process.

5. **Post-Upgrade Actions**
   - After the upgrade, remove the configuration and `gitmodules` reference with the old version.
   - Add an empty module in place of the removed references.

6. **Reupgrade**
   - Reupgrade the database and wait for the process to complete.

---

### Notes:
- Ensure that all steps are followed in sequence to avoid any issues during the upgrade process.
