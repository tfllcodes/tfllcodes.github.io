---
title: "First Post"
date: 2019-01-29T12:32:29+01:00
draft: false
---

# Writing my first article


```ruby
def test_function
  "yes"
end
```

```yml
version: '2'

services:
  seafile:
    image: some/image:1.2.3
    container_name: some-name
    restart: unless-stopped
    ports:
      - "9080:80"

    volumes:
      - some-vol:/etc/path/to/somewhere
    networks:
       - some-network

volumes:
  some-vol:
    driver: local

networks:
  some-network:
    external: true
```

And normal writing
