# EscoriasMC Modpack

Modpack del server **EscoriasMC** — Minecraft **1.21.1** + **Fabric**.

> **IP del server:** `escoriasmc.duckdns.org`

---

## Descargar

**Opcion A (zip clasico):** **[Descargar EscoriasMC-modpack-v1.0.1.zip](https://github.com/Bocchi1204/escoriasmc-modpack/releases/download/v1.0.1/EscoriasMC-modpack-v1.0.1.zip)** (147 MB)

**Opcion B (Modrinth App / Prism Launcher):** **[Descargar EscoriasMC-modpack-v1.0.1.mrpack](https://github.com/Bocchi1204/escoriasmc-modpack/releases/download/v1.0.1/EscoriasMC-modpack-v1.0.1.mrpack)** (147 MB — trae los 69 mods adentro)

### Si usas la App de Modrinth (o Prism)
1. Baja el archivo `.mrpack`
2. Abrelo con la App de Modrinth (doble clic) o en Prism: Add Instance → Import → selecciona el archivo
3. La app crea la instancia sola: Fabric, mods, configs y shaders — todo adentro del archivo
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

## Que trae el pack (69 mods)

**Mundo y contenido:** Aether, Biomes O' Plenty, Farmers Delight, Supplementaries, Supplementaries Squared, Handcrafted, Naturalist, Friends & Foes, Creeper Overhaul, Advanced Netherite, Sophisticated Backpacks, Waystones, Artifacts, Carry On, Rechiseled, Easy Magic, Elytra Slot, Double Doors, Right Click Harvest (+ compat con Supplementaries), Falling Tree, Leaves Be Gone, Nether Portal Fix, Smarter Farmers, Spawn Animations, Starter Kit

**Calidad de vida:** JEI, AppleSkin, Xaero's Minimap, Xaero's World Map, Ping Wheel, Clumps, Better Ping Display, Just Zoom, Skin Layers 3D, Durability Tooltip, Overflowing Bars, Enhanced Attack Indicator, Simple Discord RPC, etc.

**Librerias y base:** Fabric API, Architectury, GeckoLib, Cloth Config, Trinkets, Balm, Moonlight, TerraBlender, owo-lib, Resourceful Lib, Puzzles Lib, Cumulus Menus, y mas.

**Rendimiento y graficos:** ModernFix, ServerCore, Sodium, Iris (shaders), Entity Culling, Visuality

---

## Notas

- **El shader** (ComplementaryReimagined) ya viene con Iris + Sodium: se activa en Opciones → Video → Shaders.
- **No borres mods**: el server espera que todos jueguen con el mismo pack.
- Problemas al abrir? Revisa que el perfil sea **Fabric 1.21.1** con loader **0.19.5**.
- Requisitos: **Java 21** recomendado para el server; los clientes usan el Java del launcher.

---

## Changelog

**v1.0.1**
- Farmers Delight **arreglado**: el jar de v1.0.0 era la build de NeoForge y no cargaba en Fabric. Ahora usa **Farmers Delight Refabricated 3.3.6**.
- Mods nuevos: **Supplementaries 3.9.6**, **Supplementaries Squared**, **Handcrafted** y el compat de **Right Click Harvest + Supplementaries**.
- Si ya tenias el pack v1.0.0, **vuelve a descargar v1.0.1**: el server ya esta corriendo con estos mods.

---

*EscoriasMC*
