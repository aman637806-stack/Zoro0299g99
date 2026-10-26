<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ZORO TRADER - Research & Market Education</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome Icons CDN -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&family=Playfair+Display:ital,wght@0,700;0,800;1,700&display=swap" rel="stylesheet">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        navy: {
                            950: '#040714',
                            900: '#060b1b',
                            800: '#0d152d',
                            700: '#152243'
                        },
                        gold: {
                            300: '#f6e095',
                            400: '#e5c365',
                            500: '#d4af37',
                            600: '#b38f24'
                        },
                        cyanAccent: {
                            400: '#38bdf8',
                            500: '#0ea5e9',
                            600: '#0284c7'
                        }
                    },
                    fontFamily: {
                        sans: ['Plus Jakarta Sans', 'sans-serif'],
                        serif: ['Playfair Display', 'serif']
                    }
                }
            }
        }
    </script>
    <style>
        body {
            background-color: #060b1b;
            font-family: 'Plus Jakarta Sans', sans-serif;
            color: #ffffff;
            overflow-x: hidden;
        }

        .gold-gradient-text {
            background: linear-gradient(135deg, #FFF0CA 0%, #d4af37 50%, #b38f24 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .gold-border-glow {
            box-shadow: 0 0 25px rgba(212, 175, 55, 0.4);
        }

        .cta-pulse {
            box-shadow: 0 0 25px rgba(14, 165, 233, 0.45);
            animation: pulse-glow 2.2s infinite;
        }

        @keyframes pulse-glow {
            0% {
                box-shadow: 0 0 0 0 rgba(14, 165, 233, 0.7);
            }
            70% {
                box-shadow: 0 0 0 16px rgba(14, 165, 233, 0);
            }
            100% {
                box-shadow: 0 0 0 0 rgba(14, 165, 233, 0);
            }
        }

        .bg-grid-pattern {
            background-size: 32px 32px;
            background-image: 
                linear
