# FoodRoute - Backend API

## Application Database

**Application DB Connection String:** `postgresql://db_appdb_69baed6d8d85f83ab446457a_user:KFyDHGP%40%5EYY5W%21D3PifOg%23UEA5nG2cxe@ep-empty-rain-ake9k49q.c-3.us-west-2.aws.neon.tech:5432/AppDB_69baed6d8d85f83ab446457a?sslmode=require`

## Web API

**WebApi URL:** https://webapi69baed6d8d85f83ab446457a-production.up.railway.app

**Swagger API Tester URL:** https://webapi69baed6d8d85f83ab446457a-production.up.railway.app/swagger

## Google APIs (Gemini, Maps, Speech-to-Text)

The backend can use a Google API key provided via the **GOOGLE_API_KEY** environment variable (set on Railway). Use it for Gemini LLM, Maps, and Speech-to-Text. Check **GET /api/google/status** and **GET /api/google/health** to verify the key is set and reachable.

## Recommended Tools

**Recommended SQL Editor tool (Free):** [pgAdmin](https://www.pgadmin.org/download/)

## Deployment

This backend is configured for Railway deployment using nixpacks.toml.
