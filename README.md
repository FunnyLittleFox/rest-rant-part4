# Project REST-Rant

REST-Rant is an app where users can review restaurants.

## ROUTES

| Method | Path | Purpose |
|---|---|---|
| GET | / | Home Page |
| GET | /places | Places index page | 
| POST | /places | Create new place | 
| GET | /places/new | Form page for creating a new place |
| GET | /plcase/:id | Details about a particular place |
| PUT | /places/:id | Update a particular place |
| GET | /places/:id/edit | Form page for editing an existing place |
| DELETE | /places/:id | Delete a particular place |
| POST | /places/:id/rant/:rantId | Create a rant (comment) about a particular place |
| DELETE | /places/:id/rant/:randId | Delete a rant (comment) about a particular place |
| GET | * | 404 page (matches any route not defined above) |

### PLACES

| ID | Type |
| --- | --- |
| Name | String |
| City | String |
| State | String |
| Cuisines | String |
| Pic | String |