# mf-postman
A Postman collection for Kony Mobile Fabric.

## How to use

1. From Postman click **Import** and select file *Kony Mobile Fabric API V1.1.postman_collection.json*.
2. From Postman click on the gear icon (upper right corner) and click **Manage Environments**.
3. Click **Import** and select file *Kony Mobile Fabric Env.postman_environment*.
4. Click on environment *Kony Mobile Fabric Env* and update variables `userid` and `password` with actual Kony Cloud credentials and save.
6. **Open** collection *Kony Mobile Fabric API V1.1* from the main menu to the left.
7. **Select** *Kony Mobile Fabri Env* from the dropdown in the upper right corner.


## Log in

Call service `authenticateWithKonyCloud` and get the `claims_token` from the response. Update `claims_token` variable in the environment.

## Notes:
Only some of these endpoints point to v1.1 of the API. Some are not available yet as V1.1 endpoints so they still point to V1.0.
