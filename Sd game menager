#ifndef CONFIG_H
#define CONFIG_H

#include <Arduino.h>

// ======================================================
// DISPLAY
// ======================================================
constexpr uint16_t SCREEN_WIDTH  = 320;
constexpr uint16_t SCREEN_HEIGHT = 240;
constexpr uint16_t FRAME_TIME    = 33;      // ~30 FPS

// ======================================================
// GAME
// ======================================================
constexpr uint32_t GAME_TIMEOUT            = 600000UL;
constexpr uint32_t BATTERY_UPDATE_INTERVAL = 1000UL;
constexpr uint16_t KEY_DEBOUNCE            = 150;

// ======================================================
// BATTERY
// ======================================================
constexpr float BATTERY_VOLTAGE_DIVIDER = 2.0f;
constexpr float BATTERY_MAX_VOLTAGE     = 4.2f;
constexpr float BATTERY_MIN_VOLTAGE     = 3.0f;

constexpr float ADC_REFERENCE = 3.3f;
constexpr uint16_t ADC_RESOLUTION = 4095;

// ======================================================
// MATHEMATICS
// ======================================================
constexpr float PI_VALUE = 3.14159265358979323846f;

// ======================================================
// SD CARD
// ======================================================
#define SD_GAME_PATH "/GAMES"

constexpr uint16_t MAX_GAMES      = 100;
constexpr uint16_t MAX_GAME_NAME  = 32;
constexpr uint16_t MAX_GAME_PATH  = 64;

// ======================================================
// EEPROM
// ======================================================
constexpr uint16_t EEPROM_SIZE = 512;
constexpr uint16_t EEPROM_BRIGHTNESS_ADDR = 0;

// ======================================================
// PWM
// ======================================================
constexpr uint16_t BACKLIGHT_PWM_FREQ = 5000;
constexpr uint8_t  BACKLIGHT_PWM_BITS = 8;

constexpr uint16_t BUZZER_PWM_FREQ = 1000;
constexpr uint8_t  BUZZER_PWM_BITS = 8;

// ======================================================
// PIN DEFINITIONS
// ======================================================

// TFT
constexpr uint8_t BACKLIGHT_PIN = 6;

// Boost
constexpr uint8_t BOOST_EN = 15;

// Battery
constexpr uint8_t BATTERY_PIN = 4;

// Buzzer
constexpr uint8_t BUZZER_PIN = 8;

// SD Card
constexpr uint8_t SD_CS   = 5;
constexpr uint8_t SD_MOSI = 23;
constexpr uint8_t SD_MISO = 19;
constexpr uint8_t SD_SCLK = 18;

// Keypad Rows
constexpr uint8_t ROW_PIN1 = 14;
constexpr uint8_t ROW_PIN2 = 27;
constexpr uint8_t ROW_PIN3 = 26;
constexpr uint8_t ROW_PIN4 = 25;

// Keypad Columns
constexpr uint8_t COL_PIN1 = 33;
constexpr uint8_t COL_PIN2 = 32;
constexpr uint8_t COL_PIN3 = 35;
constexpr uint8_t COL_PIN4 = 34;

// ======================================================
// KEYPAD ARRAYS
// ======================================================

constexpr uint8_t ROW_PINS[4] =
{
    ROW_PIN1,
    ROW_PIN2,
    ROW_PIN3,
    ROW_PIN4
};

constexpr uint8_t COL_PINS[4] =
{
    COL_PIN1,
    COL_PIN2,
    COL_PIN3,
    COL_PIN4
};

#endif
