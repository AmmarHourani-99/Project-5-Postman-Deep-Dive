# Project 5 — Postman Deep Dive | JSONPlaceholder API

## Overview
Advanced API testing project using Postman with automated test scripts.
This project goes beyond basic GET requests and covers POST, PUT, DELETE,
and edge case scenarios with JavaScript assertions written in Postman's
After Response scripts.

## Test Summary
| Field | Details |
|---|---|
| Tester | Ammar Hourani |
| Environment | Mac / Postman v11.84.5 |
| API Tested | JSONPlaceholder (jsonplaceholder.typicode.com) |
| Total Requests | 6 |
| Test Scripts | 16 automated assertions |
| Overall Status | Pass — All requests returned expected responses |

## Requests & Test Scripts
| Request | Method | Status | Tests |
|---|---|---|---|
| Create User | POST | 201 Created | 3 passing |
| Update User | PUT | 200 OK | 3 passing |
| Delete Post | DELETE | 200 OK | 2 passing |
| Get Single Post | GET | 200 OK | 3 passing |
| Get Invalid Post | GET | 404 Not Found | 2 passing |
| Create Post Missing Fields | POST | 201 Created | 3 passing |

## Key Concepts Demonstrated
- POST requests to create new resources
- PUT requests to update existing resources
- DELETE requests to remove resources
- Error handling — 404 for non-existent resources
- Input validation — missing fields behavior
- Automated assertions using pm.test() and pm.expect()

## Tools Used
- Postman v11.84.5
- JavaScript (Postman test scripts)
- JSONPlaceholder free REST API

## Files
- `Postman-Deep-Dive-JSONPlaceholder.postman_collection.json` — Full collection with test scripts
