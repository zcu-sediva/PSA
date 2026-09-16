# PSA ZCU

Materiály k pravděpodobnosti a statistice ve formě Jupyter notebooků. Projekt postupně zavádí základní pojmy pravděpodobnosti, náhodné veličiny a jejich rozdělení a následně přidává témata z matematické statistiky, vizualizace dat a kvantové pravděpodobnosti.

## Obsah

### Pravděpodobnost a náhodné veličiny

- `kapitola_0_vztah_pravdepodobnost_statistika.ipynb` - vztah pravděpodobnosti a statistiky.
- `kapitola_1_nahodne_jevy.ipynb` - náhodné jevy a jejich pravděpodobnost.
- `kapitola_2_podminena_pravdepodobnost.ipynb` - podmíněná pravděpodobnost a nezávislost náhodných jevů.
- `kapitola_3_nahodna_velicina.ipynb` - náhodná veličina a její charakteristiky.
- `kapitola_4_diskretni_rozdeleni.ipynb` - vybraná diskrétní rozdělení.
- `kapitola_5_spojita_rozdeleni.ipynb` - vybraná spojitá rozdělení.
- `kapitola_6_nahodny_vektor.ipynb` - náhodný vektor a jeho charakteristiky.
- `kapitola_7_operace_s_nahodnymi_velicinami.ipynb` - operace s náhodnými veličinami.

### Statistika a praktické ukázky

- `kapitola2_1_vizualizace_dat.ipynb` - histogram, KDE, boxplot, violin plot, empirická distribuční funkce, P-P graf a Q-Q graf.
- `kapitola2_2_intervalove_odhady.ipynb` - intervalové odhady, konfidenční intervaly pro střední hodnotu a práce se známým i neznámým rozptylem.
- `Kapitola_8_kvantova_pravdepodobnost_ukazky.ipynb` - Bornovo pravidlo, Bellova nerovnost CHSH, kvantová tomografie a von Neumannova entropie.
- `simulace_mravencu_interaktivni.ipynb` - připravený notebook pro interaktivní simulaci mravenců.

## Požadavky

Notebooky jsou určeny pro Python a Jupyter Notebook nebo JupyterLab. Podle konkrétního notebooku se používají zejména tyto knihovny:

- `numpy`
- `scipy`
- `matplotlib`
- `plotly`
- `seaborn`
- `sympy`
- `ipywidgets`

## Spuštění

1. Naklonujte repozitář:

   ```bash
   git clone https://github.com/zcu-sediva/PSA.git
   cd PSA
   ```

2. Nainstalujte potřebné balíčky, například:

   ```bash
   python -m pip install numpy scipy matplotlib plotly seaborn sympy ipywidgets jupyter
   ```

3. Spusťte Jupyter:

   ```bash
   jupyter notebook
   ```

Některé notebooky využívají interaktivní prvky knihovny `ipywidgets`. V prostředí JupyterLab může být pro jejich správné zobrazení potřeba mít aktuální verzi JupyterLab a `ipywidgets`.

## Repozitář

Zdrojový kód a notebooky jsou dostupné na GitHubu: <https://github.com/zcu-sediva/PSA>