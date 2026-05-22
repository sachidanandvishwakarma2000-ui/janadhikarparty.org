# janadhikarektaparty.org
Official website of Jan Adhikar Ekta. Dedicated to public service, equality and social awareness.
import { Card, CardContent } from "@/components/ui/card"; import { Button } from "@/components/ui/button"; import { motion } from "framer-motion";

export default function App() { return ( <div className="min-h-screen bg-white text-gray-800"> {/* Hero Section /} <div className="relative h-[60vh] flex items-center justify-center bg-gradient-to-r from-orange-100 via-white to-green-100"> <div className="text-center p-6"> {/ Logo */} <div className="flex justify-center mb-4"> <img
src="/mnt/data/a_wide_political_banner_poster_graphic_design_sc.png"
alt="Jan Adhikar Ekta Party Logo"
className="h-24 w-24 object-contain"
/> </div>

<motion.h1
        initial={{ opacity: 0, y: -20 }}
        animate={{ opacity: 1, y: 0 }}
        className="text-4xl md:text-6xl font-bold text-blue-900"
      >
        जन अधिकार एकता पार्टी
      </motion.h1>
      <p className="mt-4 text-lg md:text-xl text-gray-700">
        अधिकार, समानता और एकता के लिए समर्पित
      </p>
      <Button className="mt-6 px-6 py-3 text-lg">
        जुड़ें हमारे साथ
      </Button>
    </div>
  </div>

  {/* About Section */}
  <div className="max-w-5xl mx-auto p-6">
    <Card>
      <CardContent className="p-6">
        <h2 className="text-2xl font-bold mb-3">हमारा उद्देश्य</h2>
        <p>
          जन अधिकार एकता पार्टी का लक्ष्य समाज में समान अधिकार, शिक्षा,
          रोजगार और न्याय को मजबूत करना है। हम सभी वर्गों को साथ लेकर
          एक सशक्त भारत बनाने के लिए प्रतिबद्ध हैं।
        </p>
      </CardContent>
    </Card>
  </div>

  {/* Vision Section */}
  <div className="bg-gray-50 py-10">
    <div className="max-w-5xl mx-auto grid md:grid-cols-3 gap-4 p-6">
      <Card>
        <CardContent className="p-4">
          <h3 className="font-bold text-xl">शिक्षा</h3>
          <p>हर बच्चे को मुफ्त और गुणवत्तापूर्ण शिक्षा।</p>
        </CardContent>
      </Card>

      <Card>
        <CardContent className="p-4">
          <h3 className="font-bold text-xl">रोजगार</h3>
          <p>युवाओं के लिए बेहतर अवसर और रोजगार सृजन।</p>
        </CardContent>
      </Card>

      <Card>
        <CardContent className="p-4">
          <h3 className="font-bold text-xl">न्याय</h3>
          <p>हर नागरिक को समान और तेज न्याय व्यवस्था।</p>
        </CardContent>
      </Card>
    </div>
  </div>

  {/* Join Section */}
  <div className="text-center py-10">
    <h2 className="text-3xl font-bold">हमसे जुड़ें</h2>
    <p className="mt-2 text-gray-600">
      एक बेहतर समाज के निर्माण में भागीदार बनें
    </p>
    <Button className="mt-4 px-6 py-3">सदस्य बनें</Button>
  </div>

  {/* Footer */}
  <div className="bg-blue-900 text-white text-center p-4">
    © 2026 जन अधिकार एकता पार्टी | सभी अधिकार सुरक्षित
  </div>
</div>

); }
