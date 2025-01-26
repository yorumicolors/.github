<h1 valign="middle" >
  <img height="40px" src="../res/seal_sots.gif?raw=true">
  <sup>yorumi.nvim - deep code, quiet sea</sup> 
</h1>

![image](https://github.com/user-attachments/assets/e11ce5aa-2747-4724-b4c8-3695c52c6075)
> artwork from [Song of the Sea](https://www.imdb.com/title/tt1865505/)

**Yorumi** – a calming deep sea colorscheme for developers. 
Inspired by the tranquil night sea, Yorumi bathes your editor in a soothing blend of blues and greens, 
maintaining mellow vibes with low contrast between components. Your text stays razor-sharp and easy on the eyes (~8:1 contrast ratio), 
perfect for late-night coding marathons or when you crave a cozy nook. Less eye strain, more code magic. 
Dive into the soothing world of Yorumi and keep your coding cool.


As a longtime fan of the [Kanagawa](https://github.com/rebelot/kanagawa.nvim) theme by [rebelot](https://github.com/rebelot), 
I wanted to elevate the experience further. Yorumi offers a darker and cozier aesthetic, perfect for maintaining a sharp and serene coding environment.


## Applications and Extras

Ready to reduce eye strain? [Download Yorumi](https://github.com/yorumicolors/yorumi#extras) for your favorite developer tools and applications. Welcome to your cozier digital workspace! ❤️

<p>
  <a href="https://github.com/yorumicolors/yorumi.nvim">
    <img src="https://img.shields.io/badge/NeoVim-667C4B?&style=for-the-badge&logo=neovim&logoColor=white"></a>
  
  <a href="https://github.com/yorumicolors/yorumi/tree/main/get/libs/tailwindcss/">
    <img src="https://img.shields.io/badge/tailwindcss-0D2C4E?style=for-the-badge&logo=tailwind-css&logoColor=white"></a>
  
  <a href="https://github.com/yorumicolors/yorumi/tree/main/apps/terms/iterm2/">
    <img src="https://img.shields.io/badge/iterm2-060914?style=for-the-badge&logo=iterm2"></a>


  <a href="https://github.com/yorumicolors/yorumi/tree/main/get/apps/terms/alacritty/">
    <img src="https://img.shields.io/badge/alacritty-0E0D17?style=for-the-badge&logo=alacritty&logoColor=BDBFCB"></a>

  <a href="https://github.com/yorumicolors/ghostty">  
    <img src="https://img.shields.io/badge/ghostty-060914?style=for-the-badge&logo=ghostery&logoColor=BDBFCB"></a>

  <a href="https://github.com/yorumicolors/wezterm">  
    <img src="https://img.shields.io/badge/wezterm-0E0D17?style=for-the-badge&logo=wezterm&logoColor=AD8FD6"></a>
</p>

Can't find your favorite application? 
[Request a port](https://github.com/yorumicolors/yorumi/issues/new?assignees=&labels=port&projects=&template=port-request.md&title=%5BPORT%5D+%3CAPP-NAME%3E).


Love Yorumi or want to contribute? [Find out how to get involved.](https://github.com/yorumicolors#contributing)

Yorumi transforms your coding sessions into a peaceful and focused journey. Dive in, explore the palette, and see how it complements your coding style!

## Palette

![image](../res/colors/palette.png)

**Yorumi** features a deep sea palette, thoughtfully divided into six thematic color groups. Each group embodies a different element of the ocean to create a serene and focused coding environment. Utilize these colors to enhance various aspects of your editor, from syntax highlighting to UI components, ensuring a cohesive and visually appealing workspace.

<details>
  <summary>
    <h3>Yoru (夜) - Night</h3> <br> The base color group for the theme, representing dark backgrounds and neutral tones. Used for UI elements like windows, panels, and text areas to create a calm, low-contrast foundation.
  </summary>

| Color | Reference | Hex Code | Description |
|-------|-----------|----------|-------------|
| ![Yoru0](../res/colors/yoru/yoru0.png) | `yoru0` | `#060914` | Main editor background. Dark, low-contrast base for the workspace. |
| ![Yoru1](../res/colors/yoru/yoru1.png) | `yoru1` | `#0C0F1A` | Background for inactive UI elements (e.g., status lines, inactive buffers). Slightly lighter than yoru0 for subtle differentiation. |
| ![Yoru2](../res/colors/yoru/yoru2.png) | `yoru2` | `#121520` | Background for cursor lines and highlights. Slightly lighter than yoru1 to distinguish active areas without overwhelming contrast. |
| ![Yoru3](../res/colors/yoru/yoru3.png) | `yoru3` | `#1D202B` | Background for fold columns and auxiliary UI elements. Maintains cohesion with the theme while providing subtle contrast. |
| ![Yoru4](../res/colors/yoru/yoru4.png) | `yoru4` | `#343742` | Used for conceal elements, visual separators, and non-critical text. Keeps the interface clean and unobtrusive. |
| ![YorudakuViolet](../res/colors/yoru/yorudakuViolet.png) | `yorudakuViolet` | `#0E0D17` | Primary background for dialog boxes and subwindows in the alternate flavor. Also used as a main background in the secondary theme variant. |
| ![YorudakuViolet](../res/colors/yoru/yorudakuGreen.png) | `yorudakuGreen` | `#141712` | Background for positive indication buttons (non-hover state). Provides a subtle, affirmative visual cue. |
| ![YorudakuViolet](../res/colors/yoru/yorudakuBlue.png) | `yorudakuBlue` | `#0F1015` | Primary background for the alternate flavor. Also used for accented button backgrounds. Slightly muted for a softer look. |
  
</details>

<details>
  <summary>
    <h3>Tsuki (月) - Moon</h3> <br> Foreground and text color group. Represents the soft glow of moonlight, used for primary and secondary text to ensure readability against dark backgrounds.
  </summary>

| Color | Reference | Hex Code | Description |
|-------|-----------|----------|-------------|
| ![Tsuki0](../res/colors/tsuki/tsuki0.png) | `tsuki0` | `#656771` | Used for comments and less prominent text. Low-contrast to blend seamlessly with the background. |
| ![Tsuki1](../res/colors/tsuki/tsuki1.png) | `tsuki1` | `#878996` | Foreground for keywords and operators. Subtle emphasis without harsh contrast. |
| ![Tsuki2](../res/colors/tsuki/tsuki2.png) | `tsuki2` | `#A7A9B5` | Foreground for function names and variables. Ensures clarity and focus. |
| ![Tsuki3](../res/colors/tsuki/tsuki3.png) | `tsuki3` | `#BDBFCB` | Primary text color for standard text and identifiers. Optimized for readability. |
| ![TsukiViolet](../res/colors/tsuki/tsukiViolet.png) | `tsukiViolet` | `#C0BCE6` | Used for hover highlights and selection backgrounds. Enhances interactivity with a soft accent. |
| ![TsukiGreen](../res/colors/tsuki/tsukiGreen.png) | `tsukiGreen` | `#D7E1B7` | Accent color for positive or affirmative elements. |
| ![TsukiBlue](../res/colors/tsuki/tsukiBlue.png) | `tsukiBlue` | `#C6DFEC` | Accent color for interactive elements. Also a primary foreground in alternate flavors. Slightly muted for versatility. |

</details>


<details>
  <summary>
    <h3>Kuroi (黒い) - Black</h3> <br> Dark accent color group (luminosity ~20). Used for shadows, borders, and low-contrast elements to add depth and structure without overwhelming the interface.
  </summary>

| Color | Reference | Hex Code | Description |
|-------|-----------|----------|-------------|
| ![KuroiRed](../res/colors/kuroi/kuroiRed.png) | `kuroiRed` | `#4E0E0E` | Background for errors and critical alerts. High-contrast to ensure visibility and urgency. |
| ![KuroiGreen](../res/colors/kuroi/kuroiGreen.png) | `kuroiGreen` | `#1C4642` | Background for success states and Git additions. Indicates positive actions or changes. |
| ![KuroiBlue](../res/colors/kuroi/kuroiBlue.png) | `kuroiBlue` | `#0D2C4E` | Background for informational elements and Git changes. Highlights modifications or updates. |
| ![KuroiYellow](../res/colors/kuroi/kuroiYellow.png) | `kuroiYellow` | `#605006` | Background for warnings and Git text changes. Draws attention to important notices. |
| ![KuroiMagenta](../res/colors/kuroi/kuroiMagenta.png) | `kuroiMagenta` | `#4C1036` | Background for warnings and Git text changes. Provides a distinct visual cue for attention. |
| ![KuroiCyan](../res/colors/kuroi/kuroiCyan.png) | `kuroiCyan` | `#104351` | Background for warnings and Git text changes. Adds a vibrant yet subtle highlight. |
| ![KuroiViolet](../res/colors/kuroi/kuroiViolet.png) | `kuroiViolet` | `#2A1844` | Background for inactive UI elements and less prominent text. Maintains a sleek, cohesive look. |
| ![KuroiOrange](../res/colors/kuroi/kuroiOrange.png) | `kuroiViolet` | `#543407` | Background for inactive UI elements and less prominent text. Adds warmth without overwhelming the interface. |
</details>


<details>
  <summary>
    <h3>Umi (海) - Sea</h3> <br> Mid-tone color group (luminosity ~35). Represents vibrant, dynamic accents for UI elements like buttons, highlights, and interactive components.
  </summary>

| Color | Reference | Hex Code | Description |
|-------|-----------|----------|-------------|
| ![UmiRed](../res/colors/umi/umiRed.png) | `umiRed` | `#913B3B` | Foreground for highlights and active search matches. Ensures visibility without being overpowering. |
| ![UmiGreen](../res/colors/umi/umiGreen.png) | `umiGreen` | `#697F4D` | Foreground for Git additions and success notifications. Indicates positive changes clearly. |
| ![UmiBlue](../res/colors/umi/umiBlue.png) | `umiBlue` | `#42778A` | Foreground for directory names and informational text. Provides a calming, readable accent. |
| ![UmiYellow](../res/colors/umi/umiYellow.png) | `umiYellow` | `#9D672F` | Foreground for warnings and active lines. Subtle yet effective for drawing attention. |
| ![UmiMagenta](../res/colors/umi/umiMagenta.png) | `umiMagenta` | `#8D3F5A` | Foreground for string literals and special characters. Adds vibrancy while maintaining readability. |
| ![UmiCyan](../res/colors/umi/umiCyan.png) | `umiCyan` | `#478584` | Foreground for variable names and annotations. Enhances clarity and focus in code.  |
| ![UmiViolet](../res/colors/umi/umiViolet.png) | `umiViolet` | `#614686` | Foreground for buttons, links, and interactive UI elements. Adds warmth and visual interest. |
| ![UmiOrange](../res/colors/umi/umiOrange.png) | `umiOrange` | `#A06A2C` | Foreground for buttons, links, and interactive UI elements. Provides a vibrant, warm accent. |

</details>


<details>
  <summary>
    <h3>Sango (珊瑚) - Coral</h3> <br> Bright accent color group (luminosity ~55). Used for vibrant highlights, warnings, and interactive elements to add energy and focus to the interface.
  </summary>

| Color | Reference | Hex Code | Description |
|-------|-----------|----------|-------------|
| ![SangoRed](../res/colors/sango/sangoRed.png) | `sangoRed` | `#C65E53` | Foreground for errors and critical alerts. High-contrast to ensure immediate attention. |
| ![SangoGreen](../res/colors/sango/sangoGreen.png) | `sangoGreen` | `#8CB167` | Foreground for success messages and Git additions. Clearly indicates positive changes. |
| ![SangoBlue](../res/colors/sango/sangoBlue.png) | `sangoBlue` | `#597BC0` | Foreground for function names and class definitions. Adds a professional, readable accent. |
| ![SangoYellow](../res/colors/sango/sangoYellow.png) | `sangoYellow` | `#BB5D7D` | Foreground for highlights like CurSearch and IncSearch. Ensures visibility in active searches. |
| ![SangoMagenta](../res/colors/sango/sangoMagenta.png) | `sangoMagenta` | `#BB5D7D` | Foreground for method names and decorators. Adds depth and structure to code. |
| ![SangoCyan](../res/colors/sango/sangoCyan.png) | `sangoCyan` | `#67BBB9` | Foreground for type annotations and interface definitions. Enhances clarity and focus. |
| ![SangoViolet](../res/colors/sango/sangoViolet.png) | `sangoViolet` | `#8666B2` | Foreground for keywords and operators. Subtle emphasis for better readability. |
| ![SangoOrange](../res/colors/sango/sangoOrange.png) | `sangoOrange` | `#C97E4F` | Foreground for warnings and important notices. Maintains visibility without being harsh. |
</details>


<details>
  <summary>
    <h3>Kairo (海路) - Bioluminescent Sea</h3> <br> Bright, high-contrast color group (luminosity ~70). Used for vibrant highlights, active states, and critical UI elements to create a glowing, dynamic effect.
  </summary>

| Color | Reference | Hex Code | Description |
|-------|-----------|----------|-------------|
| ![KairoRed](../res/colors/kairo/kairoRed.png) | `kairoRed` | `#F47571` | Foreground for inline errors and critical issues. High-contrast for immediate visibility. |
| ![KairoGreen](../res/colors/kairo/kairoGreen.png) | `kairoGreen` | `#A9D07C` | Foreground for success indicators and Git additions. Clearly signals positive changes. |
| ![KairoBlue](../res/colors/kairo/kairoBlue.png) | `kairoBlue` | `#798DDC` | Foreground for informational messages and static highlights. Provides clarity without distraction. |
| ![KairoYellow](../res/colors/kairo/kairoYellow.png) | `kairoYellow` | `#E1C084` | Foreground for active search highlights and substitute matches. Ensures visibility during searches. |
| ![KairoMagenta](../res/colors/kairo/kairoMagenta.png) | `kairoMagenta` | `#E184AF` | Foreground for function annotations and special variables. Adds sophistication and depth. |
| ![KairoCyan](../res/colors/kairo/kairoCyan.png) | `kairoCyan` | `#85E0CB` | Foreground for interface elements and type hints. Crisp contrast for better focus and readability. |
| ![KairoViolet](../res/colors/kairo/kairoViolet.png) | `kairoViolet` | `#AD8FD6` | Foreground for complex data structures and decorators. Enhances visual hierarchy in code. |
| ![KairoOrange](../res/colors/kairo/kairoOrange.png) | `kairoOrange` | `#F8A26D` | Foreground for active highlights and selections. Adds vibrancy to interactive elements. |
</details>


## Contributing

We’re thrilled you want to contribute to **Yorumi**! While our team maintains the core theme, we rely on the community to expand Yorumi to more applications.

### How You Can Help

- **Submit Ports:** If Yorumi isn’t available for an application you use, feel free to create a port and submit a pull request [here](https://github.com/yorumicolors/yorumi)
- **Join the Organization:** After we transition the repository to our organization, active contributors will be granted maintainership to manage their respective ports.
