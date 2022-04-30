# Northstar Navs
Custom navmesh files to use with Titanfall 2 AI

Create navmeshes with Warmist and Rexx's fork of the [Recast Demo](https://github.com/r-ex/r2recast).

Export maps with Warmist's [python script](https://gist.github.com/warmist/c9efdd4d84f8f97aff806fdbb3853ac8).

## Maps

**Perfect:**
- Nothing more can be done

**Very Good:**
- Roofs have been removed so AI don't go up (Until we figure out jump points)
- Titan navmeshes don't have pilot exclusive areas
- Out of bounds areas have been removed

**Good:**
- Out of bounds areas
- May have roofs removed

**Ok:**
- Has cut down geometry but still has out of bounds areas

**Untested:**
- Doesn't have nodes for attrition to test on and have just had them generated with no optimization

| Map        | State           | Notes  |
| ------------- |:-------------:| -----:|
| mp_angel_city | Good |  |
| mp_black_water_canal | Very Good | Interiors have been removed for Titans |
| mp_coliseum | Perfect | No nodes for attrition |
| mp_colony02 | Very Good | Roofs need to be removed for grunt AI |
| mp_complex3 | Good |  |
| mp_crashsite3 | Ok | Still lots of unnecesary GEO and OOB |
| mp_drydock | Very Good | Interiors have been removed for Titans |
| mp_eden | Vary Good | Roofs might need to be removed for AI |
| mp_forwardbase_kodai | Good | AI sometimes get stuck |
| mp_glitch | Very Good | Removed roofs, extra areas out of bounds and pilot exclusive areas from Titan navs |
| mp_grave | Good | Works well but AI get stuck in places |
| mp_homestead | Very Good | Removed out of bounds areas and pilot only |
| mp_lf_deck | Untested | Some out of bounds areas need to be trimmed |
| mp_lf_meadow | Untested | Some out of bounds areas need to be trimmed |
| mp_lf_stacks | Untested | Some out of bounds areas need to be trimmed |
| mp_lf_township | Untested | Some out of bounds areas need to be trimmed |
| mp_lf_traffic | Untested | Some out of bounds areas need to be trimmed |
| mp_lf_uma | Untested | Some out of bounds areas need to be trimmed |
| mp_relic02 | Good | Removed most interiors for Titans but some of the surrounding mountains need removing|
| mp_rise | Good | Might need to test upper floors with titans |
| mp_thaw | Very Good | Removed pilot only areas from titan navs |
| mp_wargames | Very Good | Removed pits and interiors for Titans but the skip might be a problem |
