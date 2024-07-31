# Basics

The repo specifies the **CacheSim** trait as the interface required for all cache simulators, and the **ObjIdTraits** trait wrapping trait bounds for the type of objects stored in the cache. Example implementation can be found (later) in lease cache and Oz cache.



# Usage
To import, under Cargo.toml [dependencies], add

        abstract_cache = {git = "https://github.com/YYWmus/abstract_cache"}