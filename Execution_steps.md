# Commands for execution of Code Crafters Bit torrent 

- Parse Torrent File
`./your_bittorrent.sh info sample.torrent`


- Calculate info hash
`./your_bittorrent.sh info sample.torrent`

- Piece hashes
`./your_bittorrent.sh info sample.torrent`

- Discover peers
`./your_bittorrent.sh peers ~/<path to sample.torrent>`

- Peer Handshake
`./your_bittorrent.sh handshake sample.torrent <peer_ip>:<peer_port>`

- Download a piece
`./your_bittorrent.sh download_piece -o /tmp/test-piece-0 sample.torrent 0`