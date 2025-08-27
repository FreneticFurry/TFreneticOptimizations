# TModloader: FreneticOptimizations

this is just a initial creation of the github thing, currently no files (will be added later on ounce Alpha testing and up starts)
just wanted to make it preemptively as to not forget to do so later as i tend to do that

if you're looking to Alpha test Frenetic Optimizations then feel free to ask on discord and ill have you on standby B) (if i dont forget again... i get sidetracked abit, mb)

as a note, im wanting to try again and the optimizations mod but the mod might/ can be dropped for other projects

# Roadmap

as a note these can change at any time something be added or removed

1. Particle limiting (only allow so many particles and have a buffer to hold particles so new particles can still spawn if they wasnt held for to long)
2. Clustered projectiles (if we have for example 3 projectiles all going roughly the same way and will hit roughly the same spot just combine them together)
3. Clustered enemies (similar to clustered projectiles)
4. AI Changes (disable an ai eg. a zombie that is in a pocket with no way to reach the player, no need to keep the ai on rather just letting it stand still until any sort of pat)
5. LOD Updates (if something like a projectile, enemy, particle is at some range from the player it will simplify or switch to a lower ticked update so things that are important to the player is updated smoother rather then things outside)
6. Render Scale option (simplifying things like collisions and textures)
7. Texture size limit (some mods make very high textures when the game primarily uses low textures, this basically would just force limit it for lower end machines)
8. Dynamic Simplification (depending on FPS will first check particles > ai > texture size > collisions and limit things that are determined as less important

these features are just me speculating on what is causing performance loss, i dont know how to use a profiler with TModLoader/ Terraria but im trying to ask around and look into it - if you know how to profile TModLoader/ Terraria please lmk! it would help alot 🙏

& finally as a fair warning: im not the best at coding but i prefer trying rather then using AI "vibe coding" doesnt vibe with me.
to the people telling me to just use AI to speed up the creation: please stop asking me to, all that does is make me really uncomfortable.
