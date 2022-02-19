# How to Fatch SpaceX Launches misstion data using GraphQL API
## Sample
![alt text](https://github.com/OloshMostisko/gqlspacex-misstion/blob/main/public/image/img1.PNG)
### End Point

https://api.spacex.land/graphql/
### Query

```sql
{
  launchesPast(limit: 10) {
    id
    mission_name
  }
}
```

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.


