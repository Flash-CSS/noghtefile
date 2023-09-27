# noghtefile
in dotfile mane bedon arayesh ham fane  bodo biya inja ke babam najare :D





# arian komak
# install cloudflared packge for start arian komak commend :D
# ghable inke arian komak bezanid cloudflared ro nasb konid :D
export DISPLAY=:1

arian() {
    ins="$1"
    case "$ins" in
        komak)
            echo "motmaen sho vpn et vasle for fuck sake"
            sudo systemctl start sshd
            sudo systemctl start cloudflared
            ;;
        mersi)
            sudo systemctl stop cloudflared
            sudo systemctl stop sshd
            echo "khahesh"
            cowsay "na man faghat azat script e vpn mikham, baghiar>
            ;;
        *)
            echo "ridi, arian <komak,mersi>" > /dev/stderr
            return 1
    esac
}
# Ye agha pouyaye gol hast ke dot filash kheili khobe mitonid berizid
https://github.com/NotMurPh/DotFiles 
