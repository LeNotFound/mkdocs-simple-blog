# Fonts

January 17, 2023

---

## 字体加载控制

主题默认加载 Google Fonts (Fira Mono)。如果你不想使用 Google Fonts，可以通过设置 `font: false` 来禁用它们：

- 默认: 自动加载 Google Fonts
- 禁用 Google Fonts: 设置 `font: false`

```yml
theme:
  font: false  # 禁用 Google Fonts 加载
```

**注意**: 设置 `font: false` 后，网站将使用浏览器默认字体或你自定义的 CSS 字体。其他字体样式设置（如 `site_name_style` 和 `title_style`）仍然有效。

## Changing the fonts

### Site name style

- Default: normal

```yml
theme:
  site_name_style: normal
```

<button style-site-name="normal">
    <code class="normal" style="background: var(--color-white) !important; color: #000000 !important;">normal</code>
</button>
<button style-site-name="bold">
    <code class="bold" style="background: var(--color-white) !important; color: #000000 !important;">bold</code>
</button>
<button style-site-name="italic">
    <code class="italic" style="background: var(--color-white) !important; color: #000000 !important;">italic</code>
</button>
<button style-site-name="scratched">
    <code class="scratched" style="background: var(--color-white) !important; color: #000000 !important;">scratched</code>
</button>
<button style-site-name="underline">
    <code class="underline" style="background: var(--color-white) !important; color: #000000 !important;">underline</code>
</button>
<button style-site-name="overline">
    <code class="overline" style="background: var(--color-white) !important; color: #000000 !important;">overline</code>
</button>


### Title style

- Default: bold

```yml
theme:
  title_style: bold
```

<button style-title="normal">
    <code class="normal" style="background: var(--color-white) !important; color: #000000 !important;">normal</code>
</button>
<button style-title="bold">
    <code class="bold" style="background: var(--color-white) !important; color: #000000 !important;">bold</code>
</button>
<button style-title="italic">
    <code class="italic" style="background: var(--color-white) !important; color: #000000 !important;">italic</code>
</button>
<button style-title="scratched">
    <code class="scratched" style="background: var(--color-white) !important; color: #000000 !important;">scratched</code>
</button>
<button style-title="underline">
    <code class="underline" style="background: var(--color-white) !important; color: #000000 !important;">underline</code>
</button>
<button style-title="overline">
    <code class="overline" style="background: var(--color-white) !important; color: #000000 !important;">overline</code>
</button>
