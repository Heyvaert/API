# API
GET / search / 1 / track? Q = true + genegenheid HTTP / 1.1 Accepteren: application / json
//..
GET /search/1/track.json?q=true+affection HTTP / 1.1
*$
<? xml version = "1.0" encoding = "UTF-8"?>
<tracks xmlns: opensearch = "http://a9.com/-/spec/opensearch/1.1/" xmlns = "http://www.spotify.com/ns/music/1">
  <OpenSearch: Query rol = "verzoek" startpagina = "1" zoektermen = "Lykke li" />
  <OpenSearch: totalResults> 117 </ opensearch: totalResults>
  <OpenSearch: startIndex> 0 </ opensearch: startIndex>
  <OpenSearch: itemsPerPage> 100 </ opensearch: itemsPerPage>
  <spoor href = "Spotify: spoor: 6PZDPg3dZgJkNL6nVMUB4b">
    <name> Little Bit </ name>
    <kunstenaar href = "Spotify: artist: 6oBm8HB0yfrIc9IHbxs6in">
      <name> Lykke Li </ name>
    </ kunstenaar>
    <album href = "Spotify: album: 6zBW3pmU291VbFHq4EdU8C">
      <name> Youth Novels </ name>
      <vrijgegeven> 2008 </ vrijgegeven>
      <beschikbaarheid>
        <bezittingen> FI NO SE </ bezittingen>
      </ beschikbaarheid>
      ...
