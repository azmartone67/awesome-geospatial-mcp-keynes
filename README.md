# Awesome Geo MCP [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Curated list of [Model Context Protocol](https://modelcontextprotocol.io) servers for geospatial work.

Entries assume no endorsement — check activity/last-commit before depending on anything; MCP tooling in this space moves fast.

## Contents

- [Geocoding, Routing & Location Services](#geocoding-routing--location-services)
- [Spatial Transformations & Geometry](#spatial-transformations--geometry)
- [Spatial Databases & Cloud-Native Geospatial](#spatial-databases--cloud-native-geospatial)
- [Earth Observation & Satellite Imagery](#earth-observation--satellite-imagery)
- [Earth Embeddings & Foundation Models](#earth-embeddings--foundation-models)
- [Contributing](#contributing)
- [License](#license)
- [Related Lists & Resources](#related-lists--resources)

## Geocoding, Routing & Location Services

- [Baidu Map MCP Server](https://github.com/baidu-maps/mcp)
- [DC Hub](https://github.com/azmartone67/dchub-mcp-server) — Live data-center site-selection data layer; Data Center Power Index (DCPI) daily grid-power scores across 300+ markets (94 tools at https://dchub.cloud/mcp)
- [Esri geospatial MCP](https://glama.ai/mcp/servers/integrations/esri)
- [Mapbox MCP Server](https://github.com/mapbox/mcp-server)
- [OSM MCP](https://github.com/NERVsystems/osmmcp)

## Spatial Transformations & Geometry

- [gis-mcp](https://github.com/mahdin75/gis-mcp)
- [qgis-mcp](https://github.com/nkarasiak/qgis-mcp)
- [qgis_mcp](https://github.com/jjsantos01/qgis_mcp)

## Spatial Databases & Cloud-Native Geospatial

- [duckdb_mcp](https://duckdb.org/community_extensions/extensions/duckdb_mcp)
- [geoflow-stac-mcp](https://github.com/chrislyonsKY/geoflow-stac-mcp)
- [geoserver-mcp](https://github.com/mahdin75/geoserver-mcp)
- [Geospatial Power Pack](https://github.com/aws-samples/sample-geospatial-kiro-power-pack) — 19 modular MCP servers for Kiro: STAC/vector/geocoding/terrain/weather data connectors, CRS/geometry/raster/point-cloud/3D processing, H3/S2 indexing, FM embeddings and embedding search, plus optional Redshift, commercial imagery, and AWS Batch/EMR/SageMaker compute
- [MCP Data Server](https://github.com/boettiger-lab/mcp-data-server)
- [PostGIS MCP Server](https://www.pulsemcp.com/servers/receptopalak-postgis)
- [PostGIS Yukon MCP](https://mcp.aibase.com/server/1574493290131366134)
- [Wherobots MCP Server](https://docs.wherobots.com/develop/mcp/mcp-server-overview)

## Earth Observation & Satellite Imagery

- [copernicus-mcp](https://github.com/wb1016/copernicus-mcp)
- [Earth Engine MCP Server](https://lobehub.com/mcp/dhenenjay-earth-engine-mcp-new)
- [earthdata-mcp-server](https://github.com/datalayer/earthdata-mcp-server)
- [IBM STAC MCP Server](https://github.com/IBM/chuk-mcp-stac)
- [NASA Earthdata MCP](https://github.com/nasa/earthdata-mcp)
- [Planetary Computer MCP](https://github.com/isaaccorley/planetary-computer-mcp)

## Earth Embeddings & Foundation Models

The [LGND MCP Server](https://github.com/EarthLegend/developer_resources/tree/main/mcp) (beta) is the first dedicated Earth-embeddings MCP server — agents can search collections by text, image, or coordinates, run inference to create new embedding collections, and inspect chips/cells.

- [Element 84 Geospatial Tech Radar](https://element84.com/geospatial-tech-radar-25/)
- [Hugging Face MCP Server](https://huggingface.co/docs/hub/en/agents-mcp)
- [LGND MCP Server](https://github.com/EarthLegend/developer_resources/tree/main/mcp)

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work.

## Related Lists & Resources

- [best-of-mcp-servers](https://github.com/tolkonepiu/best-of-mcp-servers)
- [Element 84 Geospatial Tech Radar](https://element84.com/geospatial-tech-radar-25/)
- [Kiro](https://kiro.dev/) — AWS agentic development environment that hosts the Geospatial Power Pack
- [Registry of Open Data on AWS](https://registry.opendata.aws/) — open geospatial datasets (Sentinel-2, Landsat, NASA SWOT, LGND Clay embeddings) used by the pack's default pipelines
