---
layout: default
---

# Technical Server Information

---

### spigot.yml
```
config-version: 12
settings:
  log-named-deaths: true
  debug: false
  bungeecord: false
  moved-wrongly-threshold: 0.0625
  moved-too-quickly-multiplier: 10.0
  log-villager-deaths: true
  timeout-time: 60
  restart-on-crash: true
  restart-script: ./start.sh
  netty-threads: 4
  sample-count: 12
  player-shuffle: 0
  user-cache-size: 1000
  save-user-cache-on-stop-only: true
  attribute:
    maxHealth:
      max: 2048.0
    movementSpeed:
      max: 2048.0
    attackDamage:
      max: 2048.0
messages:
  whitelist: You are not whitelisted on this server!
  unknown-command: Unknown command. Type "/help" for help.
  server-full: The server is full!
  outdated-client: Outdated client! Please use {0}
  outdated-server: Outdated server! I'm still on {0}
  restart: Server is restarting
advancements:
  disable-saving: false
  disabled:
  - minecraft:story/disabled
commands:
  replace-commands:
  - setblock
  - summon
  - testforblock
  - tellraw
  log: true
  tab-complete: 0
  send-namespaced: true
  spam-exclusions:
  - /skill
  silent-commandblock-console: false
players:
  disable-saving: false
stats:
  disable-saving: false
  forced-stats: {}
world-settings:
  default:
    verbose: false
    hopper-amount: 1
    dragon-death-sound-radius: 0
    seed-village: 10387312
    seed-desert: 14357617
    seed-igloo: 14357618
    seed-jungle: 14357619
    seed-swamp: 14357620
    seed-monument: 10387313
    seed-shipwreck: 165745295
    seed-ocean: 14357621
    seed-outpost: 165745296
    seed-endcity: 10387313
    seed-slime: 987234911
    seed-bastion: 30084232
    seed-fortress: 30084232
    seed-mansion: 10387319
    seed-fossil: 14357921
    seed-portal: 34222645
    max-tnt-per-tick: 100
    enable-zombie-pigmen-portal-spawns: true
    item-despawn-rate: 6000
    view-distance: default
    wither-spawn-sound-radius: 0
    arrow-despawn-rate: 800
    trident-despawn-rate: 1200
    hanging-tick-frequency: 100
    zombie-aggressive-towards-villager: true
    nerf-spawner-mobs: true
    mob-spawn-range: 8
    end-portal-sound-radius: 0
    max-entity-collisions: 8
    merge-radius:
      exp: 6.0
      item: 4.0
    growth:
      cactus-modifier: 100
      cane-modifier: 100
      melon-modifier: 100
      mushroom-modifier: 100
      pumpkin-modifier: 100
      sapling-modifier: 100
      beetroot-modifier: 100
      carrot-modifier: 100
      potato-modifier: 100
      wheat-modifier: 100
      netherwart-modifier: 100
      vine-modifier: 100
      cocoa-modifier: 100
      bamboo-modifier: 100
      sweetberry-modifier: 100
      kelp-modifier: 100
    entity-activation-range:
      animals: 6
      monsters: 6
      raiders: 12
      misc: 12
      water: 6
      villagers: 32
      flying-monsters: 32
      villagers-work-immunity-after: 100
      villagers-work-immunity-for: 20
      villagers-active-for-panic: true
      tick-inactive-villagers: false
      wake-up-inactive:
        animals-max-per-tick: 4
        animals-every: 1200
        animals-for: 100
        monsters-max-per-tick: 8
        monsters-every: 400
        monsters-for: 100
        villagers-max-per-tick: 4
        villagers-every: 600
        villagers-for: 100
        flying-monsters-max-per-tick: 8
        flying-monsters-every: 200
        flying-monsters-for: 100
    ticks-per:
      hopper-transfer: 8
      hopper-check: 1
    hunger:
      jump-walk-exhaustion: 0.05
      jump-sprint-exhaustion: 0.2
      combat-exhaustion: 0.1
      regen-exhaustion: 6.0
      swim-multiplier: 0.01
      sprint-multiplier: 0.1
      other-multiplier: 0.0
    max-tick-time:
      tile: 50
      entity: 50
    squid-spawn-range:
      min: 45.0
    entity-tracking-range:
      players: 48
      animals: 48
      monsters: 48
      misc: 32
      other: 64

```

### paper.yml
```
verbose: false
use-display-name-in-quit-message: false
config-version: 21
settings:
  enable-player-collisions: true
  incoming-packet-spam-threshold: 300
  save-empty-scoreboard-teams: false
  region-file-cache-size: 256
  load-permissions-yml-before-plugins: true
  suggest-player-names-when-null-tab-completions: true
  log-named-entity-deaths: true
  bungee-online-mode: true
  use-alternative-luck-formula: false
  chunk-tasks-per-tick: 1000
  console-has-all-permissions: false
  player-auto-save-rate: -1
  max-player-auto-save-per-tick: -1
  max-joins-per-tick: 3
  track-plugin-scoreboards: false
  fix-entity-position-desync: true
  watchdog:
    early-warning-every: 5000
    early-warning-delay: 10000
  spam-limiter:
    tab-spam-increment: 1
    tab-spam-limit: 500
    recipe-spam-increment: 1
    recipe-spam-limit: 20
  book-size:
    page-max: 2560
    total-multiplier: 0.98
  console:
    enable-brigadier-highlighting: true
    enable-brigadier-completions: true
  loggers:
    deobfuscate-stacktraces: true
  item-validation:
    display-name: 8192
    loc-name: 8192
    lore-line: 8192
    book:
      title: 8192
      author: 8192
      page: 16384
  velocity-support:
    enabled: false
    online-mode: false
    secret: ''
  async-chunks:
    threads: -1
  unsupported-settings:
    allow-permanent-block-break-exploits: false
    allow-piston-duplication: false
    allow-headless-pistons: false
    allow-permanent-block-break-exploits-readme: This setting controls if players
      should be able to break bedrock, end portals and other intended to be permanent
      blocks.
    allow-piston-duplication-readme: This setting controls if player should be able
      to use TNT duplication, but this also allows duplicating carpet, rails and potentially
      other items
    allow-headless-pistons-readme: This setting controls if players should be able
      to create headless pistons.
  use-display-name-in-quit-message: false
timings:
  url: https://timings.aikar.co/
  enabled: true
  verbose: true
  server-name-privacy: false
  hidden-config-entries:
  - database
  - settings.bungeecord-addresses
  - settings.velocity-support.secret
  history-interval: 300
  history-length: 3600
  server-name: Unknown Server
messages:
  no-permission: '&cI''m sorry, but you do not have permission to perform this command.
    Please contact the server administrators if you believe that this is in error.'
  kick:
    flying-player: Flying is not enabled on this server
    flying-vehicle: Flying is not enabled on this server
    authentication-servers-down: ''
    connection-throttle: Connection throttled! Please wait before reconnecting.
world-settings:
  default:
    map-item-frame-cursor-update-interval: 10
    piglins-guard-chests: true
    ender-dragons-death-always-places-dragon-egg: false
    optimize-explosions: true
    disable-teleportation-suffocation-check: false
    delay-chunk-unloads-by: 10s
    disable-creeper-lingering-effect: false
    duplicate-uuid-resolver: saferegen
    duplicate-uuid-saferegen-delete-range: 32
    phantoms-do-not-spawn-on-creative-players: true
    phantoms-only-attack-insomniacs: true
    update-pathfinding-on-block-update: true
    fix-wither-targeting-bug: false
    allow-player-cramming-damage: false
    allow-using-signs-inside-spawn-protection: false
    should-remove-dragon: false
    max-auto-save-chunks-per-tick: 6
    baby-zombie-movement-modifier: 0.5
    fixed-chunk-inhabited-time: -1
    use-vanilla-world-scoreboard-name-coloring: false
    remove-corrupt-tile-entities: false
    experience-merge-max-value: -1
    prevent-moving-into-unloaded-chunks: true
    count-all-mobs-for-spawning: false
    per-player-mob-spawns: false
    falling-block-height-nerf: 0
    tnt-entity-height-nerf: 0
    filter-nbt-data-from-spawn-eggs-and-related: true
    max-entity-collisions: 2
    map-item-frame-cursor-limit: 128
    seed-based-feature-search: true
    seed-based-feature-search-loads-chunks: true
    water-over-lava-flow-speed: 5
    grass-spread-tick-rate: 4
    use-faster-eigencraft-redstone: true
    fix-items-merging-through-walls: false
    keep-spawn-loaded: true
    armor-stands-do-collision-entity-lookups: true
    parrots-are-unaffected-by-player-movement: false
    nether-ceiling-void-damage-height: 0
    only-players-collide: false
    allow-vehicle-collisions: true
    allow-non-player-entities-on-scoreboards: false
    portal-search-radius: 128
    portal-create-radius: 16
    portal-search-vanilla-dimension-scaling: true
    container-update-tick-rate: 1
    disable-thunder: false
    skeleton-horse-thunder-spawn-chance: 0.01
    disable-ice-and-snow: false
    disable-explosion-knockback: false
    fix-climbing-bypassing-cramming-rule: false
    keep-spawn-loaded-range: 10
    prevent-tnt-from-moving-in-water: false
    show-sign-click-command-failure-msgs-to-player: false
    iron-golems-can-spawn-in-air: false
    max-leash-distance: 10.0
    armor-stands-tick: true
    non-player-arrow-despawn-rate: -1
    creative-arrow-despawn-rate: -1
    spawner-nerfed-mobs-should-jump: false
    entities-target-with-follow-range: false
    zombies-target-turtle-eggs: true
    zombie-villager-infection-chance: -1.0
    all-chunks-are-slime-chunks: false
    mob-spawner-tick-rate: 2
    light-queue-size: 20
    auto-save-interval: -1
    enable-treasure-maps: true
    treasure-maps-return-already-discovered: false
    generator-settings:
      flat-bedrock: false
    mobs-can-always-pick-up-loot:
      zombies: false
      skeletons: false
    game-mechanics:
      disable-pillager-patrols: false
      scan-for-legacy-ender-dragon: true
      fix-curing-zombie-villager-discount-exploit: true
      disable-chest-cat-detection: true
      nerf-pigmen-from-nether-portals: false
      shield-blocking-delay: 5
      disable-player-crits: false
      disable-sprint-interruption-on-attack: false
      disable-end-credits: false
      disable-unloaded-chunk-enderpearl-exploit: true
      disable-relative-projectile-velocity: false
      disable-mob-spawner-spawn-egg-transformation: false
      pillager-patrols:
        spawn-chance: 0.2
        spawn-delay:
          per-player: false
          ticks: 12000
        start:
          per-player: false
          day: 5
    hopper:
      cooldown-when-full: true
      disable-move-event: false
    mob-effects:
      undead-immune-to-certain-effects: true
      spiders-immune-to-poison-effect: true
      immune-to-wither-effect:
        wither: true
        wither-skeleton: true
    spawn-limits:
      monsters: -1
      animals: -1
      water-animals: -1
      water-ambient: -1
      ambient: -1
    alt-item-despawn-rate:
      enabled: false
      items:
        COBBLESTONE: 300
    tick-rates:
      sensor:
        villager:
          secondarypoisensor: 40
      behavior:
        villager:
          validatenearbypoi: -1
    entity-per-chunk-save-limit:
      fireball: -1
      small_fireball: -1
      experience_orb: -1
      snowball: -1
      ender_pearl: -1
      arrow: -1
    wandering-trader:
      spawn-minute-length: 1200
      spawn-day-length: 24000
      spawn-chance-failure-increment: 25
      spawn-chance-min: 25
      spawn-chance-max: 75
    door-breaking-difficulty:
      zombie:
      - HARD
      vindicator:
      - NORMAL
      - HARD
    max-growth-height:
      cactus: 3
      reeds: 3
      bamboo:
        max: 16
        min: 11
    fishing-time-range:
      MinimumTicks: 100
      MaximumTicks: 600
    despawn-ranges:
      soft: 32
      hard: 128
    frosted-ice:
      enabled: true
      delay:
        min: 20
        max: 40
    lootables:
      auto-replenish: false
      restrict-player-reloot: true
      reset-seed-on-fill: true
      max-refills: -1
      refresh-min: 12h
      refresh-max: 2d
    anti-xray:
      enabled: false
      engine-mode: 1
      max-block-height: 64
      update-radius: 2
      lava-obscures: false
      use-permission: false
      hidden-blocks:
      - copper_ore
      - deepslate_copper_ore
      - gold_ore
      - deepslate_gold_ore
      - iron_ore
      - deepslate_iron_ore
      - coal_ore
      - deepslate_coal_ore
      - lapis_ore
      - deepslate_lapis_ore
      - mossy_cobblestone
      - obsidian
      - chest
      - diamond_ore
      - deepslate_diamond_ore
      - redstone_ore
      - deepslate_redstone_ore
      - clay
      - emerald_ore
      - deepslate_emerald_ore
      - ender_chest
      replacement-blocks:
      - stone
      - oak_planks
    viewdistances:
      no-tick-view-distance: -1
    unsupported-settings:
      fix-invulnerable-end-crystal-exploit: true
    squid-spawn-height:
      maximum: 0.0
```


### bukkit.yml
```
settings:
  allow-end: true
  warn-on-overload: true
  permissions-file: permissions.yml
  update-folder: update
  plugin-profiling: false
  connection-throttle: 4000
  query-plugins: true
  deprecated-verbose: default
  shutdown-message: Server closed
  minimum-api: none
spawn-limits:
  monsters: 50
  animals: 8
  water-animals: 2
  water-ambient: 10
  ambient: 1
chunk-gc:
  period-in-ticks: 400
ticks-per:
  animal-spawns: 400
  monster-spawns: 1
  water-spawns: 1
  water-ambient-spawns: 1
  ambient-spawns: 1
  autosave: 6000
aliases: now-in-commands.yml
```

### Server.properties 
```
enable-jmx-monitoring=false
rcon.port=25575
level-seed=
enable-command-block=false
gamemode=survival
enable-query=false
generator-settings=
level-name=world
motd=\u00A7aPrivate 1.17.1 Server\u00A7c |\u00A7b New Update\: Visit https\://wrelksmc.github.io
query.port=25565
hellworld=true
pvp=true
generate-structures=true
difficulty=hard
network-compression-threshold=256
require-resource-pack=false
max-tick-time=60000
max-players=5
use-native-transport=true
online-mode=true
enable-status=true
allow-flight=false
broadcast-rcon-to-ops=true
view-distance=10
resource-pack-prompt=
server-ip=0.0.0.0
allow-nether=true
server-port=25565
enable-rcon=false
sync-chunk-writes=true
op-permission-level=4
prevent-proxy-connections=false
resource-pack=
entity-broadcast-range-percentage=100
rcon.password=
player-idle-timeout=0
force-gamemode=false
debug=false
rate-limit=0
hardcore=false
white-list=true
broadcast-console-to-ops=true
spawn-npcs=true
spawn-animals=true
snooper-enabled=true
function-permission-level=2
level-type=default
text-filtering-config=
spawn-monsters=true
enforce-whitelist=false
resource-pack-sha1=
spawn-protection=0
max-world-size=29999984
```

[back](./)
