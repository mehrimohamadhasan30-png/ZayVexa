# کیت‌های کامل رنک‌های ZAYVEXA

**نسخه سند:** 1.0  
**بازی هدف:** Minecraft Java 1.20.1  
**وضعیت:** طرح کیت‌ها برای بازبینی و تست؛ هنوز به معنی نصب افزونه‌ها یا تأیید سازگاری همه آیتم‌ها نیست.  
**ترتیب رنک‌ها:** Member → Neon → Cyber → Overdrive → Singularity → Sponsor

## اصول طراحی

1. همه بازیکنان از ابتدا به محتوای Slimefun دسترسی دارند؛ رنک‌ها دسترسی انحصاری ایجاد نمی‌کنند، بلکه تجهیزات شروع، منابع و ظرفیت تولید بیشتری می‌دهند.
2. Member باید از همان ابتدا شبکه ذخیره‌سازی واقعی و یک فارم داست قابل راه‌اندازی داشته باشد.
3. مسیر تولید به‌صورت تدریجی پیش می‌رود: فارم داست → اولین Ingot Former → تمام فلزات پایه → آلیاژها → تولید Infinity.
4. از **Ingot Former** و **Infinity Ingot Former** افزونه InfinityExpansion استفاده می‌شود؛ **Electric Ingot Factory** در طراحی کیت‌ها استفاده نمی‌شود.
5. نام ماشین‌های FastMachines مطابق فهرست ۱۶ ماشین اصلی این افزونه است. در Sponsor دو عدد از هر نوع، مستقیم داخل کیت داده می‌شود؛ برای آن‌ها شالکر FastMachines جداگانه وجود ندارد.
6. Radiant Backpack می‌تواند داخل Network Shulker باشد؛ خود شالکر نباید داخل Backpack قرار بگیرد.
7. نام‌ها و تعدادهای آیتم‌های افزونه‌ای باید با بیلد نهایی مخصوص Minecraft 1.20.1 در محیط آزمایشی تطبیق داده شوند. هر موردی که نسخه هدف در آن تأیید نشده، در بخش ریسک‌ها مشخص شده است.

---

# تجهیزات عمومی هر رنک

این بخش به همه کیت‌ها اضافه می‌شود و در هر رنک ارتقا پیدا می‌کند.

## زره

| رنک | مجموعه زره | انچنت پیشنهادی روی هر قطعه |
|---|---|---|
| Member | Netherite Armor کامل | Protection IV, Unbreaking III, Mending |
| Neon | Netherite Armor کامل | Protection V, Unbreaking IV, Mending |
| Cyber | Netherite Armor کامل | Protection VI, Unbreaking V, Mending |
| Overdrive | Netherite Armor کامل | Protection VII, Unbreaking VI, Mending |
| Singularity | Infinity Expansion: Infinity Crown, Infinity Chestplate, Infinity Leggings, Infinity Boots | Protection VIII, Unbreaking VIII, Mending |
| Sponsor | Infinity Expansion: Infinity Crown, Infinity Chestplate, Infinity Leggings, Infinity Boots | Protection IX, Unbreaking IX, Mending |

**یادداشت تعادل:** Protection بالاتر از IV و Unbreaking بالاتر از III از سقف عادی انچنت در وانیلا فراتر می‌رود. این سطوح فقط در صورت پشتیبانی روش اعطای آیتم و تست واقعی روی Paper 1.20.1 قابل استفاده‌اند. اگر تست ناموفق بود، سطح مجاز وانیلا جایگزین می‌شود.

## ابزارهای عمومی

هر کیت شامل موارد زیر است:
- Netherite Pickaxe با Fortune
- Netherite Pickaxe جداگانه با Silk Touch
- Netherite Axe
- Netherite Shovel
- Netherite Hoe
- Shears
- Fishing Rod

| رنک | Efficiency روی ابزارهای اصلی | Fortune روی کلنگ Fortune |
|---|---:|---:|
| Member | 30 | III |
| Neon | 40 | IV |
| Cyber | 50 | V |
| Overdrive | 60 | VI |
| Singularity | 75 | VII |
| Sponsor | 90 | VIII |

برای کلنگ Silk Touch، انچنت Silk Touch جایگزین Fortune می‌شود. سطح‌های Efficiency بالاتر از V و Fortune بالاتر از III نیز نیازمند تست روش اعطای انچنت سفارشی هستند.

## غذا و اقلام کاربردی

| رنک | Cooked Beef | Golden Apple | Enchanted Golden Apple | Golden Carrot |
|---|---:|---:|---:|---:|
| Member | 64 | 8 | — | 16 |
| Neon | 64 | 16 | 1 | 24 |
| Cyber | 64 | 24 | 2 | 32 |
| Overdrive | 64 | 32 | 4 | 48 |
| Singularity | 64 | 48 | 8 | 64 |
| Sponsor | 64 | 64 | 16 | 64 |

## اقلام کاربردی و سفر

| رنک | Shield | Ender Pearl | Water Bucket | Firework Rocket | Elytra |
|---|---:|---:|---:|---:|---:|
| Member | 1 | 16 | 1 | 16 | — |
| Neon | 1 | 24 | 1 | 32 | — |
| Cyber | 1 | 32 | 1 | 64 | 1 |
| Overdrive | 1 | 48 | 1 | 64 | 1 |
| Singularity | 1 | 64 | 1 | 128 | 1 |
| Sponsor | 1 | 64 | 1 | 192 | 2 |

---

# 1. MEMBER — Network Starter

**هدف:** بازیکن از روز اول شبکه ذخیره‌سازی، ابزارهای مدیریت و یک خط تولید داست داشته باشد.

## A. مجموعه Network

| آیتم | تعداد |
|---|---:|
| Network Controller | 1 |
| Network Grid | 1 |
| Network Crafting Grid | 1 |
| Network Bridge | 12 |
| Network Cell | 4 |
| Network Quantum Storage (4K) | 2 |
| Network Monitor | 2 |
| Network Importer | 1 |
| Network Exporter | 1 |
| Network Grabber | 2 |
| Network Pusher | 2 |
| Network Vacuum | 1 |
| Network Capacitor (1) | 2 |
| Network Power Outlet (1) | 1 |
| Network Power Display | 1 |
| Network Purger | 1 |

## B. فارم داست

| ماشین | تعداد |
|---|---:|
| Basic Cobble Generator | 1 |
| Dust Extractor | 1 |
| Electric Gold Pan | 1 |
| Electric Dust Washer | 1 |
| Electric Ore Grinder | 1 |

## C. انرژی و Cargo

| آیتم | تعداد |
|---|---:|
| Basic Solar Panel | 4 |
| Coal Generator | 2 |
| Energy Regulator | 1 |
| Energy Connector | 8 |
| Small Energy Capacitor | 4 |
| Medium Energy Capacitor | 2 |
| Cargo Manager | 1 |
| Cargo Motor | 2 |
| Cargo Node (Connector) | 4 |
| Cargo Node (Input) | 2 |
| Cargo Node (Output) | 2 |

## D. قطعات و مواد اولیه

| آیتم | تعداد |
|---|---:|
| Basic Circuit Board | 16 |
| Machine Circuit | 8 |
| Machine Core | 2 |
| Iron Dust | 16 |
| Gold Dust | 16 |
| Copper Dust | 16 |
| Tin Dust | 16 |
| Redstone Alloy Ingot | 8 |

## E. زره، ابزار، غذا و سفر

- Netherite Armor کامل با انچنت‌های بخش تجهیزات عمومی
- دو Netherite Pickaxe: یکی Fortune III و یکی Silk Touch
- Netherite Axe, Shovel, Hoe، Shears و Fishing Rod با Efficiency 30 روی ابزارهای قابل انچنت
- Cooked Beef ×64
- Golden Apple ×8
- Golden Carrot ×16
- Shield ×1
- Ender Pearl ×16
- Water Bucket ×1
- Firework Rocket ×16

---

# 2. NEON — Ingot Starter

**هدف:** گسترش خط داست و شروع تولید اینگات با Ingot Former.

## A. مجموعه Network

| آیتم | تعداد |
|---|---:|
| Network Controller | 1 |
| Network Grid | 1 |
| Network Crafting Grid | 1 |
| Network Bridge | 16 |
| Network Cell | 8 |
| Network Quantum Storage (4K) | 2 |
| Network Quantum Storage (32K) | 2 |
| Network Quantum Storage (262K) | 1 |
| Network Monitor | 3 |
| Network Importer | 2 |
| Network Exporter | 2 |
| Network Grabber | 4 |
| Network Pusher | 4 |
| Network Vacuum | 1 |
| Network Purger | 1 |
| Network Capacitor (1) | 2 |
| Network Capacitor (2) | 2 |
| Network Power Outlet (1) | 2 |
| Network Power Display | 1 |
| Network Recipe Encoder | 1 |
| Network Auto Crafter | 1 |

## B. فارم و تولید

| ماشین | تعداد |
|---|---:|
| Basic Cobble Generator | 2 |
| Dust Extractor | 2 |
| Ingot Former | 1 |
| Electric Gold Pan | 1 |
| Electric Dust Washer | 1 |
| Electric Ore Grinder | 1 |

## C. انرژی و Cargo

| آیتم | تعداد |
|---|---:|
| Basic Solar Panel | 4 |
| Advanced Solar Panel | 4 |
| Coal Generator | 2 |
| Energy Regulator | 1 |
| Energy Connector | 12 |
| Medium Energy Capacitor | 4 |
| Big Energy Capacitor | 2 |
| Cargo Manager | 1 |
| Cargo Motor | 4 |
| Cargo Node (Connector) | 8 |
| Cargo Node (Input) | 2 |
| Cargo Node (Output) | 3 |
| Advanced Cargo Node (Output) | 1 |

## D. اینگات‌های شروع

| آیتم | تعداد |
|---|---:|
| Iron Ingot | 16 |
| Gold Ingot (4-Carat) | 16 |
| Copper Ingot | 16 |
| Tin Ingot | 16 |

همراه با Iron Dust، Gold Dust، Copper Dust و Tin Dust، از هرکدام 32 عدد.

## E. زره، ابزار، غذا و سفر

- Netherite Armor کامل با Protection V و Unbreaking IV و Mending
- دو Netherite Pickaxe: Fortune IV و Silk Touch
- Netherite Axe, Shovel, Hoe، Shears و Fishing Rod با Efficiency 40 روی ابزارهای قابل انچنت
- Cooked Beef ×64
- Golden Apple ×16
- Enchanted Golden Apple ×1
- Golden Carrot ×24
- Shield ×1
- Ender Pearl ×24
- Water Bucket ×1
- Firework Rocket ×32

---

# 3. CYBER — Industrial Network

**هدف:** دسترسی به تمام فلزات پایه، شبکه بزرگ‌تر و آغاز استفاده از FastMachines.

## A. مجموعه Network

| آیتم | تعداد |
|---|---:|
| Network Controller | 1 |
| Network Grid | 1 |
| Network Crafting Grid | 1 |
| Network Bridge | 24 |
| Network Cell | 12 |
| Network Quantum Storage (262K) | 2 |
| Network Quantum Storage (2M) | 2 |
| Network Quantum Storage (16M) | 1 |
| Network Monitor | 4 |
| Network Importer | 4 |
| Network Exporter | 4 |
| Network Grabber | 6 |
| Network Pusher | 6 |
| Network Vacuum | 2 |
| Network Greedy Block | 1 |
| Network Capacitor (2) | 2 |
| Network Capacitor (3) | 1 |
| Network Power Outlet (1) | 2 |
| Network Power Outlet (2) | 1 |
| Network Power Display | 2 |
| Network Recipe Encoder | 2 |
| Network Auto Crafter | 2 |
| Network Auto Crafter (Withholding) | 1 |
| Network Quantum Workbench | 1 |
| Network Wireless Transmitter | 1 |
| Network Wireless Receiver | 1 |

## B. فارم داست و اینگات

| ماشین | تعداد |
|---|---:|
| Basic Cobble Generator | 2 |
| Advanced Cobble Generator | 1 |
| Dust Extractor | 2 |
| Ingot Former | 2 |
| Electric Gold Pan | 2 |
| Electric Dust Washer | 2 |
| Electric Ore Grinder | 2 |
| Electric Smeltery | 1 |
| Advanced Smeltery | 1 |

## C. انرژی و Cargo

| آیتم | تعداد |
|---|---:|
| Basic Solar Panel | 4 |
| Advanced Solar Panel | 4 |
| Combustion Reactor | 1 |
| Energy Regulator | 1 |
| Energy Connector | 16 |
| Big Energy Capacitor | 4 |
| Large Energy Capacitor | 2 |
| Cargo Manager | 1 |
| Cargo Motor | 6 |
| Cargo Node (Connector) | 12 |
| Cargo Node (Input) | 4 |
| Cargo Node (Output) | 4 |
| Advanced Cargo Node (Output) | 2 |
| Crafting Motor | 1 |

## D. تمام فلزات پایه

| آیتم | تعداد |
|---|---:|
| Iron Ingot | 16 |
| Gold Ingot (4-Carat) | 16 |
| Copper Ingot | 16 |
| Tin Ingot | 16 |
| Silver Ingot | 16 |
| Aluminum Ingot | 16 |
| Lead Ingot | 16 |
| Zinc Ingot | 16 |
| Magnesium Ingot | 16 |

از هر 9 نوع Dust نیز 16 عدد.

## E. FastMachines

| ماشین | تعداد |
|---|---:|
| Fast Crafting Table | 1 |
| Fast Furnace | 1 |
| Fast Ore Crusher | 1 |
| Fast Grind Stone | 1 |

## F. زره، ابزار، غذا و سفر

- Netherite Armor کامل با Protection VI و Unbreaking V و Mending
- دو Netherite Pickaxe: Fortune V و Silk Touch
- Netherite Axe, Shovel, Hoe، Shears و Fishing Rod با Efficiency 50 روی ابزارهای قابل انچنت
- Cooked Beef ×64
- Golden Apple ×24
- Enchanted Golden Apple ×2
- Golden Carrot ×32
- Shield ×1
- Ender Pearl ×32
- Water Bucket ×1
- Firework Rocket ×64
- Elytra ×1

---

# 4. OVERDRIVE — Advanced Production

**هدف:** تولید آلیاژها، توسعه اتوماسیون و ورود به FastMachines پیشرفته‌تر.

## A. مجموعه Network

| آیتم | تعداد |
|---|---:|
| Network Controller | 1 |
| Network Grid | 1 |
| Network Crafting Grid | 1 |
| Network Bridge | 32 |
| Network Cell | 16 |
| Network Quantum Storage (2M) | 2 |
| Network Quantum Storage (16M) | 2 |
| Network Quantum Storage (134M) | 1 |
| Network Monitor | 6 |
| Network Importer | 5 |
| Network Exporter | 5 |
| Network Grabber | 8 |
| Network Pusher | 8 |
| Network Control: X | 1 |
| Network Control: V | 1 |
| Network Vacuum | 2 |
| Network Greedy Block | 2 |
| Network Wireless Transmitter | 2 |
| Network Wireless Receiver | 2 |
| Network Capacitor (3) | 2 |
| Network Capacitor (4) | 1 |
| Network Power Outlet (2) | 2 |
| Network Power Display | 2 |
| Network Recipe Encoder | 3 |
| Network Auto Crafter | 3 |
| Network Auto Crafter (Withholding) | 2 |
| Network Magic Auto Crafter | 1 |
| Network Quantum Workbench | 1 |
| Network Magic Workbench | 1 |
| Interdimensional Oscillator | 1 |

## B. تولید داست و اینگات

| ماشین | تعداد |
|---|---:|
| Advanced Cobble Generator | 1 |
| Dust Extractor | 3 |
| Ingot Former | 3 |
| Electric Gold Pan | 2 |
| Electric Dust Washer | 2 |
| Electric Ore Grinder | 2 |
| Electric Smeltery | 2 |
| Advanced Smeltery | 1 |

## C. انرژی و Cargo

| آیتم | تعداد |
|---|---:|
| Advanced Solar Panel | 4 |
| Carbonado Solar Generator | 4 |
| Combustion Reactor | 2 |
| Energy Regulator | 1 |
| Energy Connector | 20 |
| Large Energy Capacitor | 4 |
| Carbonado Edged Energy Capacitor | 2 |
| Energized Energy Capacitor | 1 |
| Cargo Manager | 1 |
| Cargo Motor | 8 |
| Cargo Node (Connector) | 16 |
| Cargo Node (Input) | 4 |
| Cargo Node (Output) | 6 |
| Advanced Cargo Node (Output) | 3 |

## D. تمام فلزات پایه و 17 آلیاژ

- تمام 9 فلز پایه: از هرکدام 32 اینگات.
- تمام 17 آلیاژ: از هرکدام 16 عدد.
- از هر 9 نوع Dust: تعداد 32 عدد.

فهرست 17 آلیاژ:
Aluminum Brass, Aluminum Bronze, Billon, Brass, Bronze, Cobalt, Corinthian Bronze, Damascus Steel, Duralumin, Ferrosilicon, Gilded Iron, Hardened Metal, Nickel, Redstone Alloy, Reinforced Alloy, Solder, Steel.

## E. FastMachines

| ماشین | تعداد |
|---|---:|
| Fast Crafting Table | 1 |
| Fast Furnace | 1 |
| Fast Ore Crusher | 1 |
| Fast Grind Stone | 1 |
| Fast Enhanced Crafting Table | 1 |
| Fast Compressor | 1 |
| Fast Smeltery | 1 |
| Fast Ore Washer | 1 |

## F. زره، ابزار، غذا و سفر

- Netherite Armor کامل با Protection VII و Unbreaking VI و Mending
- دو Netherite Pickaxe: Fortune VI و Silk Touch
- Netherite Axe, Shovel, Hoe، Shears و Fishing Rod با Efficiency 60 روی ابزارهای قابل انچنت
- Cooked Beef ×64
- Golden Apple ×32
- Enchanted Golden Apple ×4
- Golden Carrot ×48
- Shield ×1
- Ender Pearl ×48
- Water Bucket ×1
- Firework Rocket ×64
- Elytra ×1

---

# 5. SINGULARITY — Quantum Industry

**هدف:** شروع خط تولید Infinity و شبکه کوانتومی با ظرفیت بالا.

## A. مجموعه Network

| آیتم | تعداد |
|---|---:|
| Network Controller | 1 |
| Network Grid | 1 |
| Network Crafting Grid | 1 |
| Network Bridge | 40 |
| Network Cell | 24 |
| Network Quantum Storage (16M) | 2 |
| Network Quantum Storage (134M) | 2 |
| Network Quantum Storage (1B) | 1 |
| Network Monitor | 8 |
| Network Importer | 6 |
| Network Exporter | 6 |
| Network Grabber | 10 |
| Network Pusher | 10 |
| Network Vanilla Grabber | 2 |
| Network Vanilla Pusher | 2 |
| Network Control: X | 2 |
| Network Control: V | 2 |
| Network Vacuum | 3 |
| Network Greedy Block | 4 |
| Network Purger | 2 |
| Network Wireless Transmitter | 3 |
| Network Wireless Receiver | 3 |
| Network Capacitor (4) | 3 |
| Network Power Outlet (2) | 3 |
| Network Power Display | 3 |
| Network Recipe Encoder | 3 |
| Network Auto Crafter | 6 |
| Network Auto Crafter (Withholding) | 2 |
| Network Magic Auto Crafter | 2 |
| Network Quantum Workbench | 1 |
| Network Magic Workbench | 1 |
| Interdimensional Oscillator | 1 |

## B. کارخانه داست و اینگات

| ماشین | تعداد |
|---|---:|
| Basic Cobble Generator | 1 |
| Advanced Cobble Generator | 2 |
| Infinity Cobble Generator | 1 |
| Dust Extractor | 2 |
| Infinity Dust Extractor | 1 |
| Ingot Former | 2 |
| Infinity Ingot Former | 1 |
| Electric Gold Pan | 2 |
| Electric Dust Washer | 2 |
| Electric Ore Grinder | 2 |
| Electric Smeltery | 2 |
| Advanced Smeltery | 2 |

## C. انرژی Infinity و Cargo

| آیتم | تعداد |
|---|---:|
| Basic Solar Panel | 4 |
| Advanced Solar Panel | 4 |
| Infinity Panel | 2 |
| Infinity Reactor | 1 |
| Infinite Capacitor | 1 |
| Energized Energy Capacitor | 2 |
| Carbonado Edged Energy Capacitor | 4 |
| Energy Regulator | 1 |
| Energy Connector | 24 |
| Cargo Manager | 1 |
| Cargo Motor | 10 |
| Cargo Node (Connector) | 20 |
| Cargo Node (Input) | 6 |
| Cargo Node (Output) | 8 |
| Advanced Cargo Node (Output) | 4 |

## D. منابع

- تمام 9 فلز پایه: از هرکدام 32 اینگات.
- تمام 17 آلیاژ: از هرکدام 32 عدد.
- از هر 9 نوع Dust: تعداد 32 عدد.

## E. FastMachines

| ماشین | تعداد |
|---|---:|
| Fast Crafting Table | 1 |
| Fast Furnace | 1 |
| Fast Ore Crusher | 1 |
| Fast Grind Stone | 1 |
| Fast Enhanced Crafting Table | 1 |
| Fast Compressor | 1 |
| Fast Smeltery | 1 |
| Fast Ore Washer | 1 |
| Fast Armor Forge | 1 |
| Fast Pressure Chamber | 1 |
| Fast Magic Workbench | 1 |
| Fast Table Saw | 1 |

## F. زره، ابزار، غذا و سفر

- Infinity Expansion Infinity Crown, Infinity Chestplate, Infinity Leggings و Infinity Boots با Protection VIII و Unbreaking VIII و Mending
- دو Netherite Pickaxe: Fortune VII و Silk Touch
- Netherite Axe, Shovel, Hoe، Shears و Fishing Rod با Efficiency 75 روی ابزارهای قابل انچنت
- Cooked Beef ×64
- Golden Apple ×48
- Enchanted Golden Apple ×8
- Golden Carrot ×64
- Shield ×1
- Ender Pearl ×64
- Water Bucket ×1
- Firework Rocket ×128
- Elytra ×1

---

# 6. SPONSOR — Ultimate Factory

**هدف:** کامل‌ترین بسته شبکه، تولید، ذخیره‌سازی، منابع و ماشین‌آلات ZAYVEXA.

## A. مجموعه کامل Network

| آیتم | تعداد |
|---|---:|
| Network Controller | 1 |
| Network Grid | 2 |
| Network Crafting Grid | 2 |
| Network Bridge | 64 |
| Network Cell | 32 |
| Network Quantum Storage (16M) | 2 |
| Network Quantum Storage (134M) | 2 |
| Network Quantum Storage (1B) | 2 |
| Network Quantum Storage (∞) | 1 |
| Network Monitor | 12 |
| Network Importer | 8 |
| Network Exporter | 8 |
| Network Grabber | 16 |
| Network Pusher | 16 |
| Network Vanilla Grabber | 4 |
| Network Vanilla Pusher | 4 |
| Network Control: X | 2 |
| Network Control: V | 2 |
| Network Vacuum | 4 |
| Network Greedy Block | 8 |
| Network Wireless Transmitter | 4 |
| Network Wireless Receiver | 4 |
| Network Purger | 4 |
| Network Capacitor (1) | 2 |
| Network Capacitor (2) | 2 |
| Network Capacitor (3) | 2 |
| Network Capacitor (4) | 2 |
| Network Power Outlet (1) | 4 |
| Network Power Outlet (2) | 4 |
| Network Power Display | 4 |
| Network Recipe Encoder | 4 |
| Network Auto Crafter | 8 |
| Network Auto Crafter (Withholding) | 4 |
| Network Magic Auto Crafter | 4 |
| Network Quantum Workbench | 2 |
| Network Magic Workbench | 2 |
| Interdimensional Oscillator | 2 |

## B. کارخانه نهایی داست و اینگات

| ماشین | تعداد |
|---|---:|
| Basic Cobble Generator | 2 |
| Advanced Cobble Generator | 2 |
| Infinity Cobble Generator | 2 |
| Dust Extractor | 2 |
| Infinity Dust Extractor | 2 |
| Ingot Former | 2 |
| Infinity Ingot Former | 2 |
| Electric Gold Pan | 4 |
| Electric Dust Washer | 4 |
| Electric Ore Grinder | 4 |
| Electric Smeltery | 4 |
| Advanced Smeltery | 2 |

## C. نیروگاه Sponsor

| آیتم | تعداد |
|---|---:|
| Advanced Solar Panel | 4 |
| Infinity Panel | 4 |
| Infinity Reactor | 2 |
| Infinite Capacitor | 2 |
| Energized Energy Capacitor | 4 |
| Carbonado Edged Energy Capacitor | 4 |
| Energy Regulator | 2 |
| Energy Connector | 32 |
| Cargo Manager | 2 |
| Cargo Motor | 12 |
| Cargo Node (Connector) | 24 |
| Cargo Node (Input) | 8 |
| Cargo Node (Output) | 12 |
| Advanced Cargo Node (Output) | 6 |

## D. تمام منابع و اینگات‌ها

- تمام 9 فلز پایه: از هرکدام 64 اینگات.
- تمام 17 آلیاژ: از هرکدام 64 عدد.
- از هر 9 نوع Dust: تعداد 64 عدد.

فهرست 17 آلیاژ:
Aluminum Brass, Aluminum Bronze, Billon, Brass, Bronze, Cobalt, Corinthian Bronze, Damascus Steel, Duralumin, Ferrosilicon, Gilded Iron, Hardened Metal, Nickel, Redstone Alloy, Reinforced Alloy, Solder, Steel.

## E. تمام FastMachines اصلی

از هرکدام دقیقاً 2 عدد؛ مجموعاً 32 ماشین:

| ماشین | تعداد |
|---|---:|
| Fast Crafting Table | 2 |
| Fast Furnace | 2 |
| Fast Enhanced Crafting Table | 2 |
| Fast Grind Stone | 2 |
| Fast Armor Forge | 2 |
| Fast Ore Crusher | 2 |
| Fast Compressor | 2 |
| Fast Smeltery | 2 |
| Fast Pressure Chamber | 2 |
| Fast Magic Workbench | 2 |
| Fast Ore Washer | 2 |
| Fast Table Saw | 2 |
| Fast Composter | 2 |
| Fast Panning Machine | 2 |
| Fast Juicer | 2 |
| Fast Ancient Altar | 2 |

ماشین‌های وابسته به افزونه‌های جانبی در این مجموع 32تایی حساب نشده‌اند:
- Fast Infinity Workbench — نیازمند InfinityExpansion
- Fast Mob Data Infuser — نیازمند InfinityExpansion
- Fast SlimeFrame Foundry — نیازمند SlimeFrame
- Fast Infinity Workbench 2 — نیازمند InfinityExpansion2
- Fast Mob Data Infuser 2 — نیازمند InfinityExpansion2

در صورت نصب و تأیید سازگاری هر افزونه جانبی، می‌توان دو عدد از هر ماشین وابسته را به‌صورت الحاقیه به Sponsor اضافه کرد.

## F. مواد پیشرفته

| آیتم | تعداد |
|---|---:|
| Machine Circuit | 32 |
| Machine Core | 16 |
| Machine Plate | 16 |
| Advanced Circuit Board | 64 |
| Infinite Machine Circuit | 2 |
| Infinite Machine Core | 2 |
| Infinity Ingot | 1 |
| Void Ingot | 8 |
| Infinity Singularity | 1 |

## G. سه شالکر اختصاصی Sponsor

سه شالکر باقی‌مانده در طراحی Sponsor:

1. **Totem Shulker** — مجموعه توتم‌ها و آیتم‌های محافظتی؛ محتویات دقیق باید با فهرست نهایی آیتم‌های سرور تکمیل شود.
2. **Network Shulker** — ابزارهای تکمیلی شبکه و Radiant Backpack ×1. خود شالکر داخل Backpack قرار نمی‌گیرد.
3. **Supreme / Infinity Shulker** — منابع و قطعات منتخب Infinity Expansion، بدون تکرار غیرضروری اقلامی که مستقیماً در کیت تحویل داده شده‌اند.

## H. زره، ابزار، غذا و سفر

- Infinity Expansion Infinity Crown, Infinity Chestplate, Infinity Leggings و Infinity Boots با Protection IX و Unbreaking IX و Mending
- دو Netherite Pickaxe: Fortune VIII و Silk Touch
- Netherite Axe, Shovel, Hoe، Shears و Fishing Rod با Efficiency 90 روی ابزارهای قابل انچنت
- Cooked Beef ×64
- Golden Apple ×64
- Enchanted Golden Apple ×16
- Golden Carrot ×64
- Shield ×1
- Ender Pearl ×64
- Water Bucket ×1
- Firework Rocket ×192
- Elytra ×2
- Radiant Backpack ×1 (همچنین یک عدد داخل Network Shulker در صورت تأیید ظرفیت و جای‌گذاری)

---

# چک‌لیست فنی پیش از استفاده در سرور

- [ ] نسخه دقیق Slimefun و تمام افزونه‌ها برای Minecraft 1.20.1 انتخاب شود.
- [ ] Network itemها با نسخه واقعی افزونه Networks/NetworksExpansion تطبیق داده شوند.
- [ ] Dust Extractor، Infinity Dust Extractor، Ingot Former و Infinity Ingot Former در بیلد منتخب InfinityExpansion بررسی شوند.
- [ ] انرژی مصرفی تمام ماشین‌ها محاسبه و تعداد ژنراتورها بر اساس مصرف واقعی تنظیم شود؛ صرف تعداد ژنراتور به معنی تأمین برق کافی نیست.
- [ ] ماشین‌های چندسطحی Electric Gold Pan، Electric Dust Washer و Electric Ore Grinder با نام و سطح واقعی آیتم در نسخه منتخب جایگزین شوند.
- [ ] نام دقیق هر 17 آلیاژ و 9 فلز پایه با راهنمای درون‌بازی نسخه انتخابی تطبیق داده شود.
- [ ] آیتم‌های FastMachines و پنج ماشین اختیاری وابسته به افزونه‌های جانبی جداگانه تست شوند.
- [ ] سطح انچنت‌های سفارشی 30 تا 90 و Protection بالاتر از سطح وانیلا در محیط تست بررسی شوند.
- [ ] ظرفیت Backpack و سه شالکر Sponsor بررسی شود تا هیچ آیتمی به‌دلیل محدودیت خانه جا نماند.
- [ ] کیت‌ها از نظر تعادل اقتصادی، ارزش فروش مجدد و امکان تکثیر آیتم تست شوند.

## منابع فنی بررسی

- InfinityExpansion: https://github.com/Riley31415/InfinityExpansion
- فهرست آیتم‌های InfinityExpansion: https://slimefun.net/wiki/addon/infinityexpansion/
- FastMachines: https://github.com/GuizhanCraft/FastMachines
- NetworksExpansion: https://github.com/ytdd9527/NetworksExpansion
- فهرست آیتم‌های شبکه: https://slimefun.furryrefuge.com/

**یادداشت وضعیت:** این سند، مشخصات پیشنهادی کیت‌هاست. ثبت آن در مخزن به معنی نصب، تست یا تأیید سازگاری پلاگین‌ها نیست.
