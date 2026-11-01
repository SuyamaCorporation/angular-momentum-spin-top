# 12 - 角運動量 コマ 歳差運動 デモ

**slug**: angular-momentum-spin-top
**category**: practical
**build-date**: 2026-11-02

## 概要

回転するコマの歳差運動と角運動量ベクトルをリアルタイムアニメーションで可視化する教育ツール。

## 機能

- Canvas アニメーション（歳差運動するコマ）
- 角運動量ベクトル L（黄色）、重力トルク τ（赤）、歳差 Ω（緑）の可視化
- スライダー: 回転速度 ω、傾き角 θ、質量 m
- 物理量リアルタイム表示（L, τ, Ω, 歳差周期 T）
- τ = mgr sinθ、Ω = τ/L の公式に基づく計算

## 技術仕様

- Canvas API で60fps アニメーション
- requestAnimationFrame ループ
- 全 JS インライン
