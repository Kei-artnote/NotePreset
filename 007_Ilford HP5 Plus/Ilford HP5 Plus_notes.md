# Ilford HP5 Plus 分析メモ

## 元XMPの分析（名前抜き）
- モノクロ（Gray Mixer使用）。Contrast +7.5 / Highlights -23.8 / Shadows +16.3 / Blacks -11.3 / Whites +5
- トーンカーブは直線（未調整）、Clarity/Texture 0、Sharpness 10（低め）
- Gray Mixer: R+15 O+10 Y+5 G-5 Aqua-10 B-18.8（赤系を明るく・青を暗く）
- Grain 36 / Size 27.5 / Roughness 50
- カラーグレーディングで影に青(230°・Sat8)、ハイライトに黄(50°・Sat5)の色味付き

## HP5 Plus の特性（Web確認）
- ISO400、中コントラスト、非常に広いラチチュード（ハイライトは緩やかに肩を描く）
- 立方晶の粒子で35mmでは粒状感がはっきり。EI800〜3200の増感に強い
- ニュートラルで滑らかな階調。Tri-Xより低コントラスト、Delta 400より粒子が目立つ

## 差分と改善点
| 項目 | 元 | Refined | Revised |
|---|---|---|---|
| トーンカーブ | 直線 | 弱いS字 | 黒をわずかに浮かせ、肩を持たせたS字 |
| Highlights / Whites | -23.8 / +5 | -26 / +4 | -32 / 0（ロールオフ重視） |
| Shadows / Blacks | +16.3 / -11.3 | +14 / -9 | +12 / -8 |
| Gray Mixer (G/Aqua/B) | -5 / -10 / -18.8 | -3 / -8 / -15 | 0 / -6 / -12（空は中間調寄り） |
| 色味付け | 影Sat8・ハイライトSat5 | 影Sat5・ハイライトSat3 | なし（ニュートラル） |
| 粒状 (Amount/Size/Rough) | 36/27.5/50 | 38/28/52 | 42/30/56 |
| Sharpness / Clarity / Texture | 10 / 0 / 0 | 25 / +4 / +4 | 28 / +5 / +6 |

- Refined: 元の方向性は維持し、直線カーブ・低いシャープネス・色被りを整理
- Revised: HP5 Plus の実特性（中コントラスト、ニュートラル、広いラチチュード、粗めの粒子）に寄せた版
