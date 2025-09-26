graph LR
  edge-ftrkipoah[edge-ftrkipoah]
  api-ratvcop6c[api-ratvcop6c]
  worker-xckgugj[worker-xckgugj]

  edge-ftrkipoah --> api-ratvcop6c
  api-ratvcop6c --> worker-xckgugj
  edge-ftrkipoah --> worker-xckgugj

  subgraph "CDN / Edge"
    edge-ftrkipoah
  end

  subgraph "API Tier"
    api-ratvcop6c
  end

  subgraph "Background Workers"
    worker-xckgugj
  end
