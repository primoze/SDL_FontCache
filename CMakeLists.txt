cmake_minimum_required(VERSION 3.1)
project(SDL_FontCache VERSION 0.10.0 LANGUAGES C)


add_library(FontCache
    SDL_FontCache.h
    SDL_FontCache.c
)
target_include_directories(FontCache PUBLIC .)
target_link_libraries(FontCache SDL2 SDL2_ttf)

