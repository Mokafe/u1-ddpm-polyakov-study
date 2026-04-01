# u1-ddpm-polyakov-study

Phase-based notebooks, reports, and figures for beta-conditioned DDPM studies of Polyakov loop maps in 2+1D compact U(1) lattice gauge theory.

## Overview

このリポジトリは、2+1 次元 compact U(1) 有限温度格子ゲージ理論に対して、  
β 条件付き DDPM を用いて Polyakov loop map を生成・監査した実験の記録を、  
phase ごとの notebook・report・figure として整理したものです。

本リポジトリは、最終論文版というよりも、

- 実験ノートの整理
- notebook の公開
- phase ごとの検証内容の見通しをよくすること
- 後から自分でも他者でも追跡しやすくすること

を目的とした、研究アーカイブ兼メモ置き場です。

## Reading guide

初めて見る場合は、次の順番で読むのがおすすめです。

1. **Phase 1**  
   MC データ生成と前処理の出発点

2. **Phase 2a**  
   β 条件付き DDPM が、配位ごとの秩序パラメータ  
   \( M = |\bar{P}| \) の平均を再現できるかを確認

3. **Phase 2b**  
   一次統計量の先として、  
   **M 分布・空間相関関数 C(r)・vortex 密度** を監査

4. **Phase 2b ext**  
   さらにトポロジカル監査を進め、  
   **vortex 個数分布 \(N_v\)** と **vortex–antivortex 距離分布** を比較

5. **Phase 3**  
   Polyakov loop 相関から  
   **静的電荷対自由エネルギー \(F(r)/T\)** を抽出し、MC と定量比較

## Repository structure

```text
phase-1/
  notebooks/
  reports/
  images/

phase-2a/
  notebooks/
  reports/
  images/

phase-2b/
  notebooks/
  reports/
  images/

phase-2b-ext/
  notebooks/
  reports/
  images/

phase-3/
  notebooks/
  reports/
  images/
