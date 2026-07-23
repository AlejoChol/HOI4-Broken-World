# Hearts of Iron IV - Randomizer mod
## To do
- state stats randomization is... wrong. checking whether its is_coastal or is_island_state doesn't work for dockyard spawns
- industry generation is too high
- need higher building slots max
- coal needs to be way more important, must add some coal to resource focuses
- history/state should be replaced with equivalents that have no resources, manpower, special buildings
- resource prospect potential targets randomization is broken, doesn't work
- overwrite/replace_path for now-broken ai and general scripts that no longer apply to a random world (mostly done)
## Ideas
- Countries need to be positioned
- States's stats need to be fully randomized
    - determined by climate? done
    - determined by population? done
    - determined by available resources? small amounts sprinkled all over (done) + a set amount of big resource increase that also add industry
    - determined by available POTENTIAL resources? add prospecting decisions on random states.
        - There are 230 add_resource decisions, 124 in resource_prospecting
    - NOTE: Without overwritting state definition files, province-based buildings (ports, facilities, monuments) and some state data (base population, resources) cannot be modified
## Submods
- startdates add more nations to play with
- puppets have flavours (ssrs, colonies)
- re-add extra policies submod (crumbs path: gfx/interface/idea_categories.dds)
- re-add national ideas submod (done)
- re-add compatible tt60 tech submod
- add schizo special projects submods
- Be able to upgrade states through decisions, give states flavour/modifiers
    https://steamcommunity.com/workshop/filedetails/?id=3206147228

