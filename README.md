# DateTime
Patika.Dev DateTime
namespace degisken;

class Program
{
    static void Main(string[] args)
    {
       string dt = DateTime.Now.ToString("dd.MM.yyyy");
       string td = DateTime.Now.ToString("hh.mm");
       
       Console.WriteLine(dt);
       Console.WriteLine(td);
    }
}
