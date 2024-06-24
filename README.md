# libft.a

## Descripción

Este proyecto consiste en escribir tu propia librería en C, llamada `libft.a`, que incluirá un conjunto de funciones que serán herramientas muy útiles a lo largo del cursus.

## Contenido

### Archivos a entregar

- `Makefile`
- `libft.h`
- `ft_*.c`

### Funciones autorizadas

- Para algunas funciones de la Parte 2, se permite usar `malloc` y `free`.

## Estructura del Proyecto

### Parte 1 - Funciones de libc

En esta parte, deberás rehacer algunas funciones de la libc con los mismos prototipos y comportamientos que las funciones originales, pero con el prefijo `ft_`. Aquí están las funciones a implementar:

- `ft_isalpha`
- `ft_isdigit`
- `ft_isalnum`
- `ft_isascii`
- `ft_isprint`
- `ft_strlen`
- `ft_memset`
- `ft_bzero`
- `ft_memcpy`
- `ft_memmove`
- `ft_strlcpy`
- `ft_strlcat`
- `ft_toupper`
- `ft_tolower`
- `ft_strchr`
- `ft_strrchr`
- `ft_strncmp`
- `ft_memchr`
- `ft_memcmp`
- `ft_strnstr`
- `ft_atoi`

Para implementar estas dos funciones, se permite usar `malloc`:
- `ft_calloc`
- `ft_strdup`

### Parte 2 - Funciones adicionales

Estas funciones no son de la librería libc, o lo son pero de una forma diferente. Aquí tienes las funciones a implementar:

- `ft_substr`
- `ft_strjoin`
- `ft_strtrim`
- `ft_split`
- `ft_itoa`
- `ft_strmapi`
- `ft_striteri`
- `ft_putchar_fd`
- `ft_putstr_fd`
- `ft_putendl_fd`
- `ft_putnbr_fd`

### Parte Bonus

Si completas la parte obligatoria, puedes implementar funciones adicionales para manipular listas. Usa la siguiente estructura para representar un nodo de tu lista:
typedef struct s_list
{
    void *content;
    struct s_list *next;
} t_list;

