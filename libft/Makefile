CFILES := ft_atoi.c	ft_isascii.c ft_memcpy.c ft_strlcat.c ft_strrchr.c ft_bzero.c ft_isdigt.c ft_memmove.c ft_strlcpy.c ft_tolower.c ft_calloc.c ft_isprint.c ft_memset.c ft_strlen.c ft_toupper.c ft_isalnum.c ft_memchr.c ft_strchr.c	ft_strncmp.c ft_isalpha.c ft_memcmp.c ft_strdup.c ft_strnstr.c ft_substr.c ft_strjoin.c ft_strtrim.c ft_split.c ft_itoa.c ft_strmapi.c ft_striteri.c ft_putchar_fd.c ft_putstr_fd.c ft_putendl_fd.c ft_putnbr_fd.c

CC := cc
CFLAGS := -Wall -Werror -Wextra
NAME := ../libft.a
TOOBJ := $(CFILES:.c=.o)

all: $(NAME)

$(NAME): $(TOOBJ)
	@ar rcs $(NAME) $(TOOBJ)

clean:
	@rm -f $(TOOBJ)
fclean: clean
	@rm -f $(NAME)
re: fclean all
	@rm -f $(TOOBJ)

