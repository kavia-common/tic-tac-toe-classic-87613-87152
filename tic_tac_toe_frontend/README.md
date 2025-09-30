# Tic Tac Toe - Ocean Professional

A modern, minimalist Flutter Tic Tac Toe game featuring:
- Single-player (vs basic AI) and local two-player modes
- Ocean Professional theme (Blue #2563EB, Amber #F59E0B)
- Clean UI with rounded corners, subtle gradients, and shadows
- Responsive board layout
- Status banner and restart/new game controls

## Run

1. Ensure Flutter SDK (3.29+) is installed.
2. From project root:
   ```
   cd tic_tac_toe_frontend
   flutter pub get
   flutter run
   ```
3. Choose Single or Two player mode using the segmented control at the bottom. Tap cells to play.

## Structure

- lib/
  - main.dart (entry)
  - theme/app_theme.dart (Ocean theme)
  - models/game_models.dart (enums and GameState)
  - controllers/game_controller.dart (game logic + basic AI)
  - ui/
    - screens/home_screen.dart
    - widgets/board_widget.dart, board_tile.dart, status_banner.dart, control_bar.dart

## Notes

- The AI is basic but provides a reasonable challenge.
- UI follows separation of concerns with clear layering.
