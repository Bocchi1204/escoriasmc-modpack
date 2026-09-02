# EscoriasMC Modpack

Modpack del server **EscoriasMC** — Minecraft **1.21.1** + **Fabric**.

> **IP del server:** `escoriasmc.duckdns.org`

---

## Descargar

**Opcion A (zip clasico):** **[Descargar EscoriasMC-modpack-v1.0.3.zip](https://github.com/Bocchi1204/escoriasmc-modpack/releases/download/v1.0.3/EscoriasMC-modpack-v1.0.3.zip)** (148 MB)

**Opcion B (Modrinth App / Prism Launcher):** **[Descargar EscoriasMC-modpack-v1.0.3.mrpack](https://github.com/Bocchi1204/escoriasmc-modpack/releases/download/v1.0.3/EscoriasMC-modpack-v1.0.3.mrpack)** (148 MB — trae los 70 mods adentro)

**Opcion C (CurseForge App):** **[Descargar EscoriasMC-modpack-v1.0.3-curseforge.zip](https://github.com/Bocchi1204/escoriasmc-modpack/releases/download/v1.0.3/EscoriasMC-modpack-v1.0.3-curseforge.zip)** (148 MB — importar en CurseForge: Create Custom Profile → Import)

### Si usas la App de Modrinth (o Prism)
1. Baja el archivo `.mrpack`
2. Abrelo con la App de Modrinth (doble clic) o en Prism: Add Instance → Import → selecciona el archivo
3. La app crea la instancia sola: Fabric, mods, configs y shaders — todo adentro del archivo
4. Entra a Multiplayer → `escoriasmc.duckdns.org`

### Si usas la App de CurseForge (Opcion C)
1. Baja el `.zip` de CurseForge
2. En la app: **Create Custom Profile → Import** → selecciona el zip
3. Espera a que importe (los 70 mods van adentro del zip, no descarga nada extra)
4. Entra a Multiplayer → `escoriasmc.duckdns.org`

---

## Instalacion manual (zip clasico, paso a paso)

### 1. Instalar Fabric (una sola vez)
1. Entra a **https://fabricmc.net/** y descarga el **Fabric Installer**
2. Abrelo y configura:
   - Version de juego: **1.21.1**
   - Loader: **0.19.5**
3. Dale **Install** (opcion *cliente*)
4. Se crea el perfil `fabric-loader-1.21.1` en tu launcher de Minecraft

### 2. Colocar el modpack
1. Abre tu carpeta `.minecraft`:
   - **Windows:** escribe `%appdata%/.minecraft` en la barra del explorador
   - **Mac:** `~/Library/Application Support/minecraft`
   - **Linux:** `~/.minecraft`
2. Descomprime el zip descargado
3. Copia las carpetas `mods`, `config` y `shaderpacks` **dentro de** `.minecraft`
4. Si ya existia una carpeta `mods`, **borra su contenido primero** (no mezclar mods viejos)

### 3. Jugar
1. Abre Minecraft con el perfil **fabric-loader-1.21.1**
2. Multiplayer → Add server → `escoriasmc.duckdns.org`
3. A jugar

---

## Que trae el pack (70 mods)

**Mundo y contenido:** Aether, Biomes O' Plenty, Farmers Delight, Supplementaries, Supplementaries Squared, Handcrafted, Naturalist, Friends & Foes, Creeper Overhaul, Advanced Netherite, Sophisticated Backpacks, Waystones, Artifacts, Carry On, Rechiseled, Easy Magic, Elytra Slot, Double Doors, Right Click Harvest (+ compat con Supplementaries), Falling Tree, Leaves Be Gone, Nether Portal Fix, Smarter Farmers, Spawn Animations, Starter Kit

**Calidad de vida:** JEI, AppleSkin, Xaero's Minimap, Xaero's World Map, Ping Wheel, Clumps, Better Ping Display, Just Zoom, Skin Layers 3D, Durability Tooltip, Overflowing Bars, Enhanced Attack Indicator, Simple Discord RPC, etc.

**Librerias y base:** Fabric API, Architectury, GeckoLib, Cloth Config, Trinkets, Balm, Moonlight, TerraBlender, owo-lib, Resourceful Lib, Puzzles Lib, Cumulus Menus, y mas.

**Rendimiento y graficos:** ModernFix, ServerCore, Sodium, Iris (shaders), Sodium Dynamic Lights, Entity Culling, Visuality

---

## Notas

- **El shader** (ComplementaryReimagined) ya viene con Iris + Sodium: se activa en Opciones → Video → Shaders.
- **No borres mods**: el server espera que todos jueguen con el mismo pack.
- Problemas al abrir? Revisa que el perfil sea **Fabric 1.21.1** con loader **0.19.5**.
- Requisitos: **Java 21** recomendado para el server; los clientes usan el Java del launcher.

---

## Changelog

**v1.0.3**
- **Arreglado el crash de v1.0.2**: el Sodium 0.8.13 estable rompe a los mods de luces dinamicas y options API (no oficiales, el equipo de Sodium los bloquea a proposito desde 0.8.12). Se bajo Sodium a **0.8.12-beta.1** (la ultima version que los permite) y se quitaron **Sodium Options API** y **Reese's Sodium Options**, que eran incompatibles entre si por diseño.
- Queda: **Sodium 0.8.12-beta.1 + Iris 1.8.14-beta.1 + Sodium Dynamic Lights 1.0.10** — luces dinamicas funcionando.

**v1.0.2**
- **Sodium** actualizado a **0.8.13** (antes 0.6.13) e **Iris** a **1.8.14-beta.1** (antes 1.8.8). Iris 1.8.14 requiere Sodium 0.8.x, por eso van en par.
- Mods nuevos: **Sodium Dynamic Lights** 1.0.10 (luces dinamicas: la antorcha que cargas ilumina mientras caminas) y **Sodium Options API** 1.0.10 + **Reese's Sodium Options** 2.2.3.
- Mods de cliente: el server no cambia en esta version.

**v1.0.1**
- Farmers Delight **arreglado**: el jar de v1.0.0 era la build de NeoForge y no cargaba en Fabric. Ahora usa **Farmers Delight Refabricated 3.3.6**.
- Mods nuevos: **Supplementaries 3.9.6**, **Supplementaries Squared**, **Handcrafted** y el compat de **Right Click Harvest + Supplementaries**.
- Si ya tenias el pack v1.0.0, **vuelve a descargar v1.0.1**: el server ya esta corriendo con estos mods.

---

*EscoriasMC*
