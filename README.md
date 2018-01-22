## Smart City Data

These are streaming projects for city data, showing what is possible when you make valuable city data available in real time.

The current projects in this repository are:

- [Chicago 311](https://streaming-api-projects.github.io/smart-city-data/chicago-311.html)
- [San Francisco 511](https://streaming-api-projects.github.io/smart-city-data/san-francisco-511.html)
- [Baltimore 911](https://streaming-api-projects.github.io/smart-city-data/baltimore-911.html)

All projects proxy city data using [Streamdata.io](http://streamdata.io), and uses Server-Sent Events (SSE) to push updates to each existing city data JSON API, only sending what changes using JSON Patch.
